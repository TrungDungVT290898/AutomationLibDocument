
# MCProtocol

Mô tả: Thư viện dùng để giao tiếp, đọc/ghi thanh ghi PLC Mitsu với chuẩn truyền thông MCProtocol.

Link Source code: https://github.com/ping9719/McProtocol

## 1.1. Cài đặt

### 1.1.1. Cài đặt PLC

### 1.1.2. Cài đặt môi trường PC

- Visual studio 2022
- .NET Framework \>=4.6
- .NET Core \>=2.0

## 1.2. Sử dụng

Khi sử dụng thư viện MCProtocol, bạn phải hoàn thành các hướng dẫn trong mục [Cài đặt](#_exv4hx3b7fl).

### 1.2.1 Hàm đóng/ngắt kết nối:

**Task<int\> Open();**

**int Close();**

### 1.2.2Hàm đọc thanh ghi/bit:

**Task<int\> GetBitDevice(string iDeviceName, int iSize, int[] oData);**

**Task<int\> GetBitDevice(PlcDeviceType iType, int iAddress, int iSize, int[] oData);**

**Task<byte[]\> ReadDeviceBlock(string iDeviceName, int iSize, int[] oData);**

**Task<byte[]\> ReadDeviceBlock(PlcDeviceType iType, int iAddress, int iSize, int[] oData);**

**Task<byte[]\> ReadDeviceBlockByte(PlcDeviceType iType, int iAddress, int iSize);**

### 1.2.3.Hàm ghi thanh ghi/bit:

**Task<int\> SetBitDevice(string iDeviceName, int iSize, int[] iData);**

**Task<int\> SetBitDevice(PlcDeviceType iType, int iAddress, int iSize, int[] iData);**

**Task<int\> WriteDeviceBlock(string iDeviceName, int iSize, int[] iData);**

**Task<int\> WriteDeviceBlock(PlcDeviceType iType, int iAddress, int iSize, int[] iData);**

**Task<int\> WriteDeviceBlockByte(PlcDeviceType iType, int iAddress, int iSize, byte[] bData);**

**Task<int\> SetDevice(string iDeviceName, int iData);**

**Task<int\> SetDevice(PlcDeviceType iType, int iAddress, int iData);**

# II. SLMP

Mô tả: Thư viện dùng để giao tiếp, đọc/ghi thanh ghi PLC Mitsu với chuẩn truyền thông MCProtocol.

Link Source code: https://github.com/ping9719/McProtocol

## 1.1. Cài đặt

### 1.1.1. Cài đặt PLC

### 1.1.2. Cài đặt môi trường PC

- Visual studio 2022
- .NET Framework \>=4.6
- .NET Core \>=2.0

## 1.2. Sử dụng

Khi sử dụng thư viện MCProtocol, bạn phải hoàn thành các hướng dẫn trong mục [Cài đặt](#_exv4hx3b7fl).

### 1.2.1 Hàm đóng/ngắt kết nối:

**Task<int\> Open();**

**int Close();**

### 1.2.2Hàm đọc thanh ghi/bit:

**Task<int\> GetBitDevice(string iDeviceName, int iSize, int[] oData);**

**Task<int\> GetBitDevice(PlcDeviceType iType, int iAddress, int iSize, int[] oData);**

**Task<byte[]\> ReadDeviceBlock(string iDeviceName, int iSize, int[] oData);**

**Task<byte[]\> ReadDeviceBlock(PlcDeviceType iType, int iAddress, int iSize, int[] oData);**

**Task<byte[]\> ReadDeviceBlockByte(PlcDeviceType iType, int iAddress, int iSize);**

### 1.2.3.Hàm ghi thanh ghi/bit:

**Task<int\> SetBitDevice(string iDeviceName, int iSize, int[] iData);**

**Task<int\> SetBitDevice(PlcDeviceType iType, int iAddress, int iSize, int[] iData);**

**Task<int\> WriteDeviceBlock(string iDeviceName, int iSize, int[] iData);**

**Task<int\> WriteDeviceBlock(PlcDeviceType iType, int iAddress, int iSize, int[] iData);**

**Task<int\> WriteDeviceBlockByte(PlcDeviceType iType, int iAddress, int iSize, byte[] bData);**

**Task<int\> SetDevice(string iDeviceName, int iData);**

**Task<int\> SetDevice(PlcDeviceType iType, int iAddress, int iData);**