# sfbot_can

   ros2_control 프레임워크를 이용하여 SFBot 개발 프로젝트입니다. 다중 모터를 CAN 통신 인터페이스로 제어합니다.

   개발자 : foody-j  


Hardware Interface Class : SfBotSystemHardware  
namespace : sfbot_can   

CAN Communication driver header : motor_can_driver.hpp  
Motor Data Structure header : motor_data.hpp  

# 변경사항
   2025.01.21  
   motor_data.hpp 파일 수정  
      MotorData 구조체에 motor_id 추가  
      편의 함수 추가