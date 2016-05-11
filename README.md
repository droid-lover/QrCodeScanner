# QrCodeScanner
This QrCodeScanner will help you to read every Qr code 

To detect QR codes(and other types of barcodes), you should use an instance of the BarcodeDetector class. 
The following code shows you how to create one using BarcodeDetector.Builder

Barcode is nothing but an image specially for machine , to read barcode we just need a good smartphone with good quality of camera 

first we will convert the barcode image into a bitmap 

then we will set the format of what type of code you want to read , in this example i am specifyinQR codes , 
otherwise by default it will access all type of codes 

then we will apply a camera saurce to our barcode detector instance 
and it will generate a Sparse Array (where most of the elements contains default value 0 or null ) 
and we will check the size of this sparse array , if it is not null our app will generate the equivalent value of the QrCode . 

Thanks 
- maker is jarvis (sachin) here 


