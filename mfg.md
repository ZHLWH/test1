## 经纬度距离测试

<http://www.hxuwb.com:8848/hxzkoa/jingweijuli.do>

## GPS定位原理

利用GPS进行定位的基本原理就是四颗卫星定位地面一个标的物的三维坐标

由于信号传输过程中会经过电离层、对流层，导致信号的传播路径并非遵循两点之间直线最近的原则，因此又会产生对流层和电离层误差。这就导致仅仅利用GPS的四颗定位卫星无法准确的获得标的物的位置信息（误差通常在10米这个量级）。

## RTK基本概念

RTK定位技术是一种基于高精度载波相位观测值的实时动态差分定位技术(Real Time Kinematic，RTK )，基准站首先将自己获得的载波相位观测值及站点坐标，通过数据通信链实时发送给周围工作的动态用户。流动站数据处理模块使用动态差分定位的方法确定流动站相对基准站的坐标，然后根据基准站的坐标反算自身的瞬时坐标。

RTK的英文全称是（Real Time Kinematic，RTK）是实时动态载波相位差分技术的简称，是一种通过基准站和流动站的同步观测，利用载波相位观测值实现快速高精度定位功能的差分测量技术。

## GPS、RTK、PPK三种定位技术的原理及应用

[https://blog.csdn.net/u010783226/article/details/109003323?ops\_request\_misc=%257B%2522request%255Fid%2522%253A%2522166934201016800186514641%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D\&request\_id=166934201016800186514641\&biz\_id=0\&utm\_medium=distribute.pc\_search\_result.none-task-blog-2~all~sobaiduend\~default-1-109003323-null-null.142^v66^control,201^v3^control\_2,213^v2^t3\_control1\&utm\_term=RTK%E9%A2%91%E6%AE%B5\&spm=1018.2226.3001.4187](https://blog.csdn.net/u010783226/article/details/109003323?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522166934201016800186514641%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D\&request_id=166934201016800186514641\&biz_id=0\&utm_medium=distribute.pc_search_result.none-task-blog-2\~all\~sobaiduend\~default-1-109003323-null-null.142^v66^control,201^v3^control_2,213^v2^t3_control1\&utm_term=RTK%E9%A2%91%E6%AE%B5\&spm=1018.2226.3001.4187)

## **RTK的应用领域**

## 卫星系统

### 卫星系统和频点

![image.png](https://note.youdao.com/yws/res/309/WEBRESOURCEbd6878425f2b3d358b0a0c0a30a03401)

### BDS（中国）

北斗卫星导航系统（英文名称：BeiDou Navigation Satellite System，简称BDS）,是中国自行研制的[全球卫星导航系统](https://baike.baidu.com/item/%E5%85%A8%E7%90%83%E5%8D%AB%E6%98%9F%E5%AF%BC%E8%88%AA%E7%B3%BB%E7%BB%9F/3395723?fromModule=lemma_inlink) 北斗卫星导航系统由空间段、地面段和用户段三部分组成，可在全球范围内全天候、全天时为各类用户提供高精度、高可靠[定位](https://baike.baidu.com/item/%E5%AE%9A%E4%BD%8D/16912011?fromModule=lemma_inlink)、[导航](https://baike.baidu.com/item/%E5%AF%BC%E8%88%AA/7741941?fromModule=lemma_inlink)、[授时](https://baike.baidu.com/item/%E6%8E%88%E6%97%B6/1914126?fromModule=lemma_inlink)服务，并且具备短报文[通信](https://baike.baidu.com/item/%E9%80%9A%E4%BF%A1/300982?fromModule=lemma_inlink)能力，已经初步具备区域导航、定位和授时能力，[定位精度](https://baike.baidu.com/item/%E5%AE%9A%E4%BD%8D%E7%B2%BE%E5%BA%A6/5165935?fromModule=lemma_inlink)为分米、厘米级别，测速精度0.2米/秒，授时精度10纳秒。

### GPS（美国）

全球定位系统(Global Positioning System，GPS)，是一种以[人造地球卫星](https://baike.baidu.com/item/%E4%BA%BA%E9%80%A0%E5%9C%B0%E7%90%83%E5%8D%AB%E6%98%9F/377179?fromModule=lemma_inlink)为基础的高精度无线电导航的定位系统，它在全球任何地方以及近地空间都能够提供准确的地理位置、车行速度及精确的时间信息。

### GLONASS （俄罗斯）

格洛纳斯（GLONASS），是[俄语](https://baike.baidu.com/item/%E4%BF%84%E8%AF%AD/315852?fromModule=lemma_inlink)“全球卫星导航系统**GLOBAL NAVIGATION SATELLITE SYSTEM**”的缩写 ，格洛纳斯卫星导航系统作用类似于美国的[GPS](https://baike.baidu.com/item/GPS?fromModule=lemma_inlink)、欧洲的[伽利略卫星定位系统](https://baike.baidu.com/item/%E4%BC%BD%E5%88%A9%E7%95%A5%E5%8D%AB%E6%98%9F%E5%AE%9A%E4%BD%8D%E7%B3%BB%E7%BB%9F/5599567?fromModule=lemma_inlink)和中国的[北斗卫星导航系统](https://baike.baidu.com/item/%E5%8C%97%E6%96%97%E5%8D%AB%E6%98%9F%E5%AF%BC%E8%88%AA%E7%B3%BB%E7%BB%9F/10390403?fromModule=lemma_inlink)。

### Galileo（欧盟）

伽利略卫星导航系统（Galileo satellite navigation system），是由[欧盟](https://baike.baidu.com/item/%E6%AC%A7%E7%9B%9F/383198?fromModule=lemma_inlink)研制和建立的[全球卫星导航定位系统](https://baike.baidu.com/item/%E5%85%A8%E7%90%83%E5%8D%AB%E6%98%9F%E5%AF%BC%E8%88%AA%E5%AE%9A%E4%BD%8D%E7%B3%BB%E7%BB%9F/5639649?fromModule=lemma_inlink)

### QZSS（日本）

**准天顶卫星系统**（[日语](https://baike.baidu.com/item/%E6%97%A5%E8%AF%AD?fromModule=lemma_inlink)：准天顶卫星システム，[英文](https://baike.baidu.com/item/%E8%8B%B1%E6%96%87?fromModule=lemma_inlink)：**Quasi-Zenith Satellite System**；[缩写](https://baike.baidu.com/item/%E7%BC%A9%E5%86%99?fromModule=lemma_inlink)：**QZSS**）是以三颗[人造卫星](https://baike.baidu.com/item/%E4%BA%BA%E9%80%A0%E5%8D%AB%E6%98%9F?fromModule=lemma_inlink)透过[时间转移](https://baike.baidu.com/item/%E6%97%B6%E9%97%B4%E8%BD%AC%E7%A7%BB?fromModule=lemma_inlink)完成全球定位系统区域性功能的卫星扩增系统 。其发射信号与 GPS L1 C/A、L1C、L2C 和 L5 信号兼容，覆盖包 括日本和澳洲在内的太平洋地区。模块可同时接收和跟踪 QZSS 与 GPS L1 C/A 和 L5 信号，因而具有更强 的可用性，特别是在诸如城市峡谷等弱信号环境下

### SBAS

SBAS（Satellite-Based Augmentation System）即星基增强系统，通过地球静止轨道（GEO）卫星搭载卫星导航增强信号转发器，可以向用户播发星历误差、卫星钟差、电离层延迟等多种修正信息，实现对于原有卫星导航系统定位精度的改进，从而成为各航天大国竞相发展的手段。

如美国的WAAS（Wide Area Augmentation System）；由欧洲空间局（ESA）、欧盟（EC）及欧洲航行安全局（Eurocontrol）联合设计建设的EGNOS系统；日本的MSAS 系统；印度的GAGAN系统 。

### DR

航位推算法(Dead reckoning，简称DR)是一种比较经典的导航方法，广泛使用在航海、航空和车辆自动定位系统中。航位推算法是利用初始位置，结合移动速度与方向来计算出位置的过程，即通过前一个计算历元的己知位置与时间间隔，以及从前一个历元到当前解算历元的平均速度及方向来进行计算完成。通过方向角将速度分解成东向速度与北向速度两个速度分量，各分量乘以时间间隔，得出位置的变化量，通过对初始位置矢量与位置的变化量求和，获得当前位置。

### 常用CORS账号

目前国内现已建成的CORS大部分为省CORS，以省为单位，在某一个省内购买CORS服务，在本省进行RTK测量等工作均可接收到差分定位信号。
1.[全国千寻CORS](https://mall.qxwz.com/market/services/FindCM?utm_medium=ffgg\&utm_source=baidu-sem\&utm_term=%E4%B8%AD%E5%9B%BD%E7%A7%BB%E5%8A%A8cors%E8%B4%A6%E5%8F%B7%E5%AE%98%E7%BD%91)
中国兵器和阿里巴巴共建的千寻（全国）CORS是现阶段比较成熟，并且投入到生产中的全国一张网CORS系统，已经在测绘方面有较好的应用，购买服务也比较简单
2.[移动CORS](https://www.qxcors.com/ydcors?order=comment_count)
中国移动主要经营移动语音、宽带、和多媒体等业务，是国内及全球用户规模、网络规模最大的移动通讯运营商。
3.华测CORS
华测cors账号也叫"FixCM"高精度定位产品，是华测依靠自研的参考站接收机、CORS服务算法构建的一个可以让GNSS定位芯片/终端的定位精度从米级提高到亚米、厘米级甚至毫米级的高精度位置增强系统，可在除港、澳、台、西藏及少数无人区外提供7\*24小时服务。
4.北斗CORS

## RTK基线长度

常用字母D表示，为基准站到移动站的距离。

## u-center

[点击跳转](https://zhuanlan.zhihu.com/p/441684301)
u-center是ublox公司的一款通用GNSS上位机，集成了NMEA数据解析，可视化等功能，对于看NMEA协议比较方便

## 常见缩写解释

*   D:基准站到移动站距离
*   RMS:均方根误差（概率单位）
*   CORS:第三方基站账号
*   CEP:圆概率误差,定位的点在以某个半径为圆内的概率
*   H代表HDOP,水平精度因子，Horizontal dilution of precision
*   V代表VDOP竖直精度因子,Vertical dilution of precision

## 注意事项

1.使用无线传输时，空中波特率需要大于等于串口波特率，否则会出现丢数不能进入RTK定位的情况

## 定位数据
![image.png](https://note.youdao.com/yws/res/8741/WEBRESOURCEd9f71cdb2c4154747c2eda8a901a3e1d)
- **RMC** Recommended Minimum Specific GNSS Data. Time, date, position, course, and speed data provided by a GNSS receiver.
- **GGA** Global Positioning System Fix Data. Time, position, and fix-related data for a GNSS receiver.
- **GSV** GNSS Satellites in View. The GSV sentence provides the number of satellites in view (SV), satellite ID numbers, elevation, azimuth, and SNR value, and it contains maximum four satellites per transmission. Therefore, it may take several sentences to get complete information. The total number of sentences being transmitted and the sentence number are indicated in the first two data fields.
- **GSA** GNSS DOP and Active Satellites. GNSS receiver operating mode, satellites used in the navigation solution reported by the GGA sentence, and DOP values.
- **VTG** Course Over Ground & Ground Speed. The actual course and speed relative to the ground.
- **GLL** Geographic Position – Latitude/Longitude. Latitude and longitude of the GNSS receiver position, the time of position fix and status.
- **ZDA** Time & Date. UTC, day, month, year and local time zone.
- **GRS** GNSS range residuals. This sentence supports Receiver Autonomous Integrity Monitoring (RAIM). Range
- **GST** GNSS Pseudorange Error Statistics. This sentence supports Receiver Autonomous Integrity Monitoring (RAIM). Pseudorange measurement error statistics can be translated in the position domain in order to give statistical measures of the quality of the position solution. 



