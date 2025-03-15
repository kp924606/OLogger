![](https://img.shields.io/badge/Creater-TCT-FFFF00) ![](https://img.shields.io/badge/development-csharp-006400) ![](https://img.shields.io/badge/SDK-DotNet8-blue) ![](https://img.shields.io/badge/Tool-VisualStudio2022-222222) ![](https://img.shields.io/badge/OS-Windows-FF8022) ![](https://img.shields.io/badge/Type-dll-00BB00)

# OLogger
OLogger/紀錄檔案日誌

## 1. OLogger.dll
將 Log 物件，儲存成檔案.

*Save the Log object as a file.*

### 主要功能：

- 1.在專案內建立專屬的儲存物件及函式：

  *Create dedicated storage objects and functions within the project, and save them as files.*

```bash
OLogInfo? ologinfo = null;
ologinfo = new OLogInfo(Assembly.GetExecutingAssembly().GetName().Name, 30, 3, 777);
ologinfo!.Logger.Info($@"<{li.Name},{li.Class}>[{li.Method}][{li.ResultCode}] {li.Info}");
```

![image](https://github.com/user-attachments/assets/7d5985d5-fda6-4bda-9200-f708ca61039c)

------

## About Me
Thanks & Best Regards !

蔡承廷

​Senior Engineer of Semiconductor Product/Testing & ​Automation

Email: ​​kp924606@gmail.com

LinkedIn:https://www.linkedin.comin/tsai-cheng-ting/
