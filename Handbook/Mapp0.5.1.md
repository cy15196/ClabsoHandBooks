麒麟智慧软件使用说明书
======================


## 1.概述
麒麟智慧测量软件是一款智能测量软件（App），连接匹配的电子测量设备（如数码游标卡尺）后，具备自动获取测量数据、数据检查到生成测量报告等功能。整个软硬件系统如下下图所示：
<img style="width:60%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/main.png" align="center" />

图 1 麒麟智慧测量软件主页面  

<img style="width:60%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/work_flow.png" align="center" />

图2 麒麟智慧测量系统示意图

本工作流程介绍以数码游标卡尺为例进行，下文所称测量设备，如无特殊说明，均指数码游标卡尺。

<img style="width:60%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/ruler.png" align="center" />

图3 数码游标卡尺（含蓝牙发射器）

## 2.连接
本软件通过蓝牙（BLE）与测量设备进行连接通信，使用测量功能前，需要先确保蓝牙能够顺利连接。
#### 2.1打开测量设备和手机蓝牙
首先，需要将蓝牙发射器插入测量设备，并将测量设备和蓝牙发射器都打开。

<img style="width:45%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/put_bluetooth.png" align="center" />   <img style="width:45%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/open_ruler.png" align="center" />
<!-- ![](https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/put_bluetooth.png) -->

图 4 插入蓝牙发射器并打开设备

<!-- ![](https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/open_ruler.png) -->


之后，打开手机设置界面，将手机的蓝牙功能打开。

<img style="width:300px" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/open_bluetooth.png" align="center" />

图6 打开手机蓝牙功能

#### 2.2连接设备
完成2.1 中准备工作之后，即可开启软件，点击连接设置，进入连接设置页面。点击页面下方，重新连接按钮，等待10s左右，软件弹出连接成功或者连失败。

<img style="width:30%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/link_setting.png" align="center" />

图 7 连接设置页面


## 3.测量
按照使用游标卡尺的方法正常测量尺寸，确定之后，按下蓝牙发生器上的按钮，则数据往外传输，建立连接的软件端即接收到数据并进行处理（显示）。
#### 3.1自由测量
连接完成之后，即可进入通过主页面，点击自由测量，进入自由测量页面。

<img style="width:30%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/free.png" align="center" />

图 8 自由测量页面（右图为实际测量示例）
#### 3.2测量向导
根据实际需求，软件提供了测量向导的功能，用户可预先定义好需要进行测量检验的产品，之后便可按照产品中定义的顺序、测量项类型、尺寸要求等进行测量检验，完成之后生成测量结果。

<img style="width:30%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/product_manager.png" align="center" /> <img style="width:30%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/product_detail.png" align="center" />

图9 产品管理页面及详情页面

<img style="width:30%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/wazarid_item.png" align="center" /> <img style="width:30%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/wazarid_info.png" align="center" />
  
图10 测量向导（测量项，测量信息）


## 4.导出结果
通过测量向导生成测量结果之后，需要再进行一步操作，生成报告。生成的报告为Excel格式，用户可直接在手机上用其他应用查看，或者进行分享，也可连接电脑进行拷贝和同步。

<img style="width:30%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/result_list.png" align="center" />

图 11 测量历史记录页面

<img style="width:30%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/info.png" align="center" />


#### 4.1生成报告
首先，在首页上点击历史记录，进入历史记录页面。滑动列表，选中测量结果，点击生成报告，即生成Excel报告。
    
<img style="width:30%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/result_detail.png" align="center" /> <img style="width:30%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/share_report.png" align="center" />

图 12 选中记录，点击导出Excel


## 5.产品管理
产品管理包括新建，删除，编辑，查看等。直接选中对应的项，点击按钮即可。

### 5.1编辑/查看
<img style="width:30%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/item_edit.png" align="center" />

图 15 新建/编辑产品 （右图为增加/编辑测量参数项 ）

### 5.2从Excel导入 （暂未实现）
<img style="width:30%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/import_excel.png" align="center" />

### 联系我们
info@clabso.com
