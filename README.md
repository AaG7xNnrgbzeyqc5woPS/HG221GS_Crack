# HG221GS_Crack

# 破解 HG221GS超级密码:
    https://github.com/AaG7xNnrgbzeyqc5woPS/FiberHome-HG221GS-Decoder

a program to decode FiberHome HG221GS FiberCat telecomadmin password
设备类型 EPON
生产厂家 FiberHome
设备型号: HG221GS
硬件版本号: HS.V2.0
软件版本号: E60D1.00MA000

----------------------------------
# 实战:

    浏览网页: http://192.168.1.1/cgi-bin/baseinfoSet.cgi
    或者下载  wget http://192.168.1.1/cgi-bin/baseinfoSet.cgi

    我自己的内容如下:
    ---
    "RETURN":
    {"success": true},
    "BASEINFOSET":
    {"baseinfoSet_INTERNETMAC":"...",
    "baseinfoSet_TR069MAC":"...",
    "baseinfoSet_VOIPMAC":"...",
    "baseinfoSet_PRIPROTOCOLMAC":"...",
    "baseinfoSet_WLANMAC":"...",
    "baseinfoSet_PONMAC":"...",
    "baseinfoSet_INTERNETEN":"1",  //互联网开通
    "baseinfoSet_TR069EN":"1",     //管理链接开通
    "baseinfoSet_VOIPEN":"1",      //VOIP 开通
    "baseinfoSet_PRIPROTOCOLEN":"1",   // ... 协议开通?
    "baseinfoSet_QOSEN":"0", 
    "baseinfoSet_PONEN":"",  
    "baseinfoSet_TELECOMACCOUNT":"telecomadmin",  //超级用户
    "baseinfoSet_TELECOMPASSWORD":"telecomadmin12345678",  //这里是超级密码,已经被我改过了.
    "baseinfoSet_USERACCOUNT":"useradmin",   //普通用户
    "baseinfoSet_USERPASSWORD":"bcXFA",    //普通用户缺省密码
    "baseinfoSet_MANUFACTUREROUI":"F8***",  
    "baseinfoSet_DEVICESERIALNUMBER":"F8****-******",
    "baseinfoSet_MACLEARNSLEEP":"80",
    "baseinfoSet_SOFTWAREVERSION":"E50D1.14M1000",
    "baseinfoSet_EXTNUMBER":"RP020106",
    "baseinfoSet_HARDWAREVERSION":"V1.0",
    "baseinfoSet_HARDWARECODE":"WKE7.200.299R1A",
    "baseinfoSet_SSID":"ChinaNet-***********",
    "baseinfoSet_WPAKEY":"12345678",
    "baseinfoSet_WPAENCRYPT":"AESEncryption",
    "baseinfoSet_REGSTATUS":"1",    
    "baseinfoSet_EnableFastPath":"0",
    "baseinfoSet_GPONSN":"FHTT6C2651D2",
    "baseinfoSet_GPONPASSWORD":"HG26012345",
    "baseinfoSet_PONMODE":"EPON",
    "other_MSSEN":"1",
    "other_MSSVALUE":"1400",
    "wirelessenable":"0"}
    }
    //后面的是注释, 省略号,以及星号.屏蔽掉的内容
    //超级密码和普通密码都已经试过,可以登录

# 实战二
    可以查看目录,有更多信息可以挖掘
    http://192.168.1.1/cgi-bin/


