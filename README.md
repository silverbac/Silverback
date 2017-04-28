# Silverback Arduino Boards
This repository contains support for the following Silverback Arduino-compatible development boards:
# AVR Boards
1) Surilli
2) Mandrill

Each board will be added as an entry to the Arduino Tools > Board menu.
                                                   ########## Picture ##########
# Installation Instructions
To add board support for our products, go to File > Preferences, and paste this URL into the 'Additional Boards Manager URLs' input field:
//url + picture
This field can be found in 'Preferences...' under the Arduino File menu.

Now, under the Tools > Board > Boards Manager..., if you type in "Silverback", you will see an option to install board files for SparkFun Arduino compatible boards. Click "Install" to add these to your list.

//pic
Now, when you select the Boards list, you will see a collection of new boards for Silverback.
//pic

# Cleaning up the Boards Menu

Each entry in the boards list is defined in boards.txt. If you want to de-clutter the menu, you can comment out a board by inserting a # at the beginning of each line.

# Notes

Please note: This will only work under Arduino IDE versions 1.6 and up.
Information on compiling and programming the bootloaders can be found in the bootloaders directory.

