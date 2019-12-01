IO模型   即输入输出模型

java.io大包  大家族
                                CharArrayReader         BufferedReader  InputStreamReader
                    reader      StringReader            FilterReader    FileReader
        字符流(）
                    writer      CharArrayWriter         BufferedWriter  InputStreamWriter
IO流                             StringWriter           FilterWriter    FileWriter

                    InputStream   ByteArrayInputStream
                                  FileInputStream
        
        字节流(byte 8bite)
                    
                                  ByteArrayOutputStream
                    OutputStream  fileOutputStream
                    
                    
                    字节流：filterInputStream    filterOutputStream
                    DataInputStream  DataOutputStream
                    
                    
        Java的IO的装饰器模式
        BufferedInputStream