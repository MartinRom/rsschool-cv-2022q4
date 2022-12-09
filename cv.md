## Ivan Romanuk

#### Contact Information
__Address:__ Minsk, Belarus  
__E-mail:__ romanuk.ivanc@gmail.com  
__Discord:__ Martin2#0832  
__GitHub:__ MartinRom  
### About me
I do technical support, integration of cash register equipment, POS systems, bank terminals with software. I support the passing of software certification in testing centers.
### Code Example
```cs
private ResponseResault XReport()
{
    string sFullHexCommand = "04 0D";
    byte[] byteFullCommand = GetByteOut(sFullHexCommand);
    UDPSocket.SendTo(byteFullCommand, byteFullCommand.Length, SocketFlags.None, IpKsaHostEnd);
    Recieve(); 
    ResponseResault rResault = GetResponseFromKsa("XReport");
    return rResault;
}
```
### Education
Institute of Information Technology
### Languages
Russian - native  
English - A1