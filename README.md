# pros5baseBot
Basic two motor bot

This is a basic two motor based sample project to show how to setup a basic PROS program.  Please note that this code is set assuming the motor has a RED gear cartridge inserted, which is not the default.  In most cases you will want to set it to the GREEN cartridge by changing the following statement as shown:

pros::Motor left_wheel (LEFT_MOTOR_PORT, MOTOR_GEARSET_36, false, pros::E_MOTOR_ENCODER_DEGREES);

Change to green cartridge as follows:

pros::Motor left_wheel (LEFT_MOTOR_PORT, MOTOR_GEARSET_18, false, pros::E_MOTOR_ENCODER_DEGREES);
