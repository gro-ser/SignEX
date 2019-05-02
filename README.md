# SignEX
Class that allows you to scan and write memory in processes


### Usage
```cs
SignEX s = new SignEX("process_name");
s.WriteBytes(bytes_for_scan, bytes_for_write);//returns bool whether code was injected or not
```
