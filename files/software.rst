SOFTWARE
########

MOBILE APPLICATION
==================

DESCRIPTION
-----------

The OpenVenti mobile application has the purpose of monitoring and administering the artificial respirator of the same name, in a safe and intuitive way.

The system will consist of the following components:


**Estructura de la Aplicación**

.. image:: img/structure.png
  :width: 400

WORKFLOW
--------

FUNCTIONS
^^^^^^^^^

USERS
^^^^^


EMPAREJAMIENTO
^^^^^^^^^^^^^^

Usaremos la tecnología BLE, que es la que permite iOS. Trabaja sobre L2CAP. Aquí la gráfica de los protocolos.

.. image:: img/conn.png
  :scale: 75

DATA VISUALIZATION
^^^^^^^^^^^^^^^^^^

.. image:: img/datos.png
  :scale: 75

DATA TRANSIM
^^^^^^^^^^^^^^^^^^^^^

Wifi technology will be used, applying ANSI/TIA 1149 standard, reason to control the radio spectrum and not to hinder the connection of other equipment, including other fans.

The ANSI/TIA 1149 standard is used for Commercial Mobile Alert Service (CMAS) on CDMA systems 

DATA RECEPTION
^^^^^^^^^^^^^^

PANEL DE ADMINISTRACIÓN
^^^^^^^^^^^^^^^^^^^^^^^

.. image:: img/paciente.png
   :scale: 75


LOGOUT
^^^^^^

TRATAMIENTO DEL PACIENTE
------------------------

.. image:: img/paciente.png
   :scale: 75

HISTORIA CLÍNICA
^^^^^^^^^^^^^^^^

Número que identifica de manera única al paciente, incluso si regresa a la Institución. 
Puede ser utilizado el número de DNI. A obtener del HIS del lugar de atención.

PANTALLA 
--------

.. image:: img/screen.png
  :width: 400
..

Los Botones de abajo permiten modificar los siguientes parámetros:

    1) TV o Tidal Volume, que puede estar entre 450 y 600 mL
    2) PEEP o Presión positiva remanente, que puede estar entre 0 y 8 cmH2o
    3) Porcentaje de Oxígeno, que puede estar entre 0 y 50%
    4) RR o Respiration Rate o Respiraciones por minuto, que puede estar entre 9 y 16

.. include:: webserver.rst