# transfer-speed-increase-for-windows
(TR) bu komutları girerek windows işletim sistemi olan bilgisayarlarda daha hızlı bir usb aktarım hızı elde edebilirsiniz (ÖNEMLİ NOT : BU KOD SİSTEM İÇİN AYRILMIŞ VERİ TRANSFER PROTOKOLÜNÜ NORMAL TRANSFERLER İÇİN DE ÇALIŞMASINI SAĞLAR , BİLGİSAYARINIZIN SİSTEM İŞLEYİŞİ NORMAL TRANSFER YAPILIRKEN YAVAŞLAYABİLİR!!!):
(EN)By entering these commands, you can get a faster USB transfer speed on computers with Windows operating system (IMPORTANT NOTE: THIS CODE ENSURE THAT THE DATA TRANSFER PROTOCOL RESERVED FOR THE SYSTEM WORKS FOR NORMAL TRANSFERS, THE SYSTEM OPERATION OF YOUR COMPUTER MAY SLOW DOWN WHILE MAKING NORMAL TRANSFER!!!):
"""
netsh int tcp set global autotuninglevel=disabled
""" 
& 
"""
fsutil behavior set memoryusage 2
"""
