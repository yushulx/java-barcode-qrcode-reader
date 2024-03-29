# Java Barcode and QR Code Reader

The sample shows how to use [Dynamsoft Barcode Reader SDK for Java](https://www.dynamsoft.com/barcode-reader/sdk-desktop-server/) to build a simple Java barcode and QR code reader on Windows, Linux (**AMD64 and ARM64**), and macOS.

## SDK Version
[v9.0](https://www.dynamsoft.com/barcode-reader/downloads/)

## Usage

Set a valid [license key](https://www.dynamsoft.com/customer/license/trialLicense?product=dbr):

```java
BarcodeReader.initLicense("LICENSE-KEY");
```

Run the Java program in command-line tools:

```
mvn clean install assembly:assembly
java -cp target/test-1.0-SNAPSHOT-jar-with-dependencies.jar com.dynamsoft.App images/AllSupportedBarcodeTypes.png
```

![Java barcode and QR code reader](https://www.dynamsoft.com/codepool/img/2022/03/arm64-jetson-nano-java-barcode.png)

## Docker Linux Container

```
docker rmi dynamsoft/barcode-reader -f
docker build -t dynamsoft/barcode-reader -f Dockerfile .
docker run -it dynamsoft/barcode-reader
```

![Java barcode reader in Docker](https://www.codepool.biz/wp-content/uploads/2020/02/java-barcode-reader-docker.png)

## More Samples
https://github.com/Dynamsoft/barcode-reader-java-samples

## Blog
[How to Use Dynamsoft Java Barcode Reader to Scan Multiple Barcodes](https://www.dynamsoft.com/codepool/java-barcode-reader-scan-multiple.html)
