# AVR-OledSSD-1306Driver-Screen
OLED ssd1306 Driver
## Description
A bunch of Simple to use Software Interfaces are available to choose from

Bool OLED_Init();  
Bool OLED_DISPLAY_CHAR(char C);  
Bool OLED_SET_CURSOR(uint8 X,uint8 Y);  
void OLDE_ScrollRight(uint8_t Pag_start, uint8_t Pag_End);  
void OLDE_ScrollLeft(uint8_t Pag_start, uint8_t Pag_End);  
void OLED_DEACTIVATE_scroll();  
void OLED_DISPLAY();  
void OLED_Draw_Line(uint8 x_0,uint8 y_0,uint8 x_1,uint8 y_1);  
void OLED_DRAW_Vertical_LINE(uint8 Center_x,uint8 Center_y,uint8 height);  
void OLED_DRAW_HORZ_LINE(uint8 Center_x,uint8 Center_y,uint8 Width);  
void OLED_DRAW_RECTANGLE(uint8 x,uint8 y,uint8 Width,uint8 Height);  
Bool OLED_DISPLAY_String(char *str,uint8 X,uint8 Y,uint8 Font);  
Bool OLED_display_Integer(int32 Num,uint8 Col_C,uint8 Row_C,uint8 Font);  
Bool OLED_display_Float(float32 Num,uint8 Col_C,uint8 Row_C,uint8 Font);  
Bool OLED_display_Image(unsigned char *Bitmap);  
Bool OLED_SET_PIXEL(uint8 Page,uint8 Col);  
  
![image](https://user-images.githubusercontent.com/106155115/235771551-11c0e5c8-1078-458e-83c9-f7018dae0be3.png)
![image](https://user-images.githubusercontent.com/106155115/235771596-24bcbff6-960e-4339-91f2-2819dab47281.png)
### Dependencies
AVR Gcc Compiler

## Help
Please Contact me or send A message and I will respond

## Authors
Seif Eldidi
