# ESPAstroFocus
An ESP32 based remote telescope focuser.

**How to:**

 1. Tutorial on how to use the Arduino IDE with the ESP32 can be found [here](https://randomnerdtutorials.com/installing-the-esp32-board-in-arduino-ide-windows-instructions/)
 2. Install following packages: AsyncTCP, ESPAsyncWebServer and Arduino_JSON.
 
 [AsyncTCP](https://github.com/me-no-dev/AsyncTCP): Click on the green code button and click "Download ZIP". Now go to your Arduino IDE and click Sketch->Include Library->Add .ZIP library. Then select the ZIP file you downloaded.

[ESPAsyncWebServer](https://github.com/me-no-dev/ESPAsyncWebServer): Click on the green code button and click "Download ZIP". Now go to your Arduino IDE and click Sketch->Include Library->Add .ZIP library. Then select the ZIP file you downloaded.

[Arduino_JSON](https://github.com/arduino-libraries/Arduino_JSON): Click on the green code button and click "Download ZIP". Now go to your Arduino IDE and click Sketch->Include Library->Add .ZIP library. Then select the ZIP file you downloaded.

 3. To insta the SPIFFS tool, please follow [this](https://randomnerdtutorials.com/install-esp32-filesystem-uploader-arduino-ide/) tutorial.
 4. Add your own steppe motor drivers and code in the `FocusIn` and `FocusOut` methods.
 5. Upload the sketch the same way you upload a normal arduino sketch and be sure to select the correct board, which is mostly likely the ESP32 Devkit V1 but you might have to press the BOOT button on the board while uploading.
 6. To upload the webpage data, close any programs that may still be using the COM port, for example the Serial Monitor, go to Tools and press the ESP32 Sketch Data Upload, again, you might have to press the BOOT button whileuploading.
 7. Done!
