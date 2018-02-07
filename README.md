# 2017National-electronic-design-competition-for-college-students-HPU
本系统以Buck和Boost并联，实现双向DC-DC交换，以STM32为核心控制芯片。通过单片机闭环实现恒流输出控制。以L298N作为PWM控制驱动器，组成电压负反馈系统，通过调整PWM的占空比，实现稳压输出。系统能自动检测外部电源电压变化，在负载端电源较高时自动切换成充电模式，反之切换为放电状态。系统具有过流、过压保护功能，并可对输出电压、电流进行测量和显示。
