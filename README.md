# SwerveExample
WPILIB Swerve Drive Example code customized for 997 2020 robot configuration

This code used the stardard WPILIB Swerve Drive example and then I re-configured:
- Updated to use CAN based motor controllers
- Updated to use FalconSRX motors/controllers for the drive motors on the modules
- Updated to use VictorSPX controllers (CAN connected) for rotation
- Replaced encoder on rotation axis with absolute encoder
- Replaced the included gyro with a NavX IMU
