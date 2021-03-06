/**
  @page Sample 
  
  @verbatim
  ******************** (C) COPYRIGHT 2012 STMicroelectronics *******************
  * @file    SimpleMAC/Talk/readme.txt 
  * @author  MCD Application Team
  * @version V2.0.1
  * @date    30-November-2012 
  * @brief   Description of the Sample applications.
  ******************************************************************************
  *
  * Licensed under MCD-ST Liberty SW License Agreement V2, (the "License");
  * You may not use this file except in compliance with the License.
  * You may obtain a copy of the License at:
  *
  *        http://www.st.com/software_license_agreement_liberty_v2
  *
  * Unless required by applicable law or agreed to in writing, software 
  * distributed under the License is distributed on an "AS IS" BASIS, 
  * WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
  * See the License for the specific language governing permissions and
  * limitations under the Licens
  *   
  ******************************************************************************
   @endverbatim

@par Example Description 

This is an example of an RF application that demonstrates point-to-point 802.15.4 wireless
communication using the STM32W108 microcontroller.

More details about this Demo implementation is given in the User manual 
"UM0893 STM32W108xx SimpleMAC library", available for download from the ST
microcontrollers website: www.st.com/stm32w


@par Directory contents 

  - SimpleMAC/Talk/stm32w108xx_conf.h     Library Configuration file
  - SimpleMAC/Talk/stm32w108xx_it.h       Interrupt handlers header file
  - SimpleMAC/Talk/stm32w108xx_it.c       Interrupt handlers
  - SimpleMAC/Talk/talk.c                Main program
         
@par Hardware and Software environment

  - This example runs on STM32W108xx Devices.
  
  - This example has been tested with STMicroelectronics MB851 revD, MB954 revC, MB950 revB 
    and MB951 revB (STM32W108xx) boards and can be easily tailored to any other supported 
    device and development board.

  - Boards Set-up
    - Connect the boards to a PC with a USB cable through USB connector J2 to power the board 
      and to communicate with the Hypertherminal
  - Hyperterminal configuration:
    - Word Length = 8 Bits
    - One Stop Bit
    - No parity
    - BaudRate = 115200 baud
    - flow control: Disable
 
@par How to use it ? 

In order to make the program work, you must do the following :
 - Open your preferred toolchain      
 - Rebuild all files and load your image into target memory
 - Run the application

@note
 - STM32W108xx devices are STM32W108xx microcontrollers where the Flash memory 
   density ranges between 64 and 256 Kbytes.
   
 * <h3><center>&copy; COPYRIGHT STMicroelectronics</center></h3>
 */
 