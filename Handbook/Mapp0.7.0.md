麒麟智慧软件使用说明书
======================

## 1.概述
麒麟智慧测量软件是一款智能测量软件（App），连接匹配的电子测量设备（如数码游标卡尺）后，具备自动获取测量数据、数据检查到生成测量报告等功能。整个软硬件系统如下下图所示：

<img style="width:60%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/work_flow.png" align="center" />

麒麟智慧测量系统示意图

本工作流程介绍以数码游标卡尺为例进行，下文所称测量设备，如无特殊说明，均指数码游标卡尺。

<img style="width:60%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/ruler.png" align="center" />

数码游标卡尺（含蓝牙发射器）

#### 1.1 软件主页面分区

软件采用三段式布局，从上而下依次是任务栏，功能区和导航条。
* 任务栏从左至右依次为‘关于’ ， 当前页面标题和‘连接设置’页面
* 功能区将不同分类下的功能按钮按照9宫格的形式排布
* 导航条用户切换不同的功能分区

<img style="height:400px" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/main.png" align="center" />

麒麟智慧测量软件主页面  

### 1.2 主要功能分页介绍

* 关于页面
软件的版本信息，使用说明书和检查更新操作都集中于关于页面。 点击查看使用说明则打开在线的说明文档；点击检查更新，软件会自动联网检查是否存在更新版本的软件，并按照用户选择进行更新

<img style="height:400px" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/about.png" align="center" /> <img style="height:400px" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/about_handbook.png" align="center" /> 


* 连接设置
负责建立app与测量工具的蓝牙连接。打开手机蓝牙开关，并点击重新连接即可
  
<img style="height:400px" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/link_setting.png" align="center" /> <img style="height:400px" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/link_success.png" align="center" />

连接设置

* 任务
  
  任务页面包括了测量向导和自由测量两项。

* 数据
  
  数据页面包括测量的结果，产品文件，信息设置。
  
* 工具
  
  工具页面主要放置一些辅助功能，现仅完成从Excel模板文件中导入产品，查看图纸功能还在开发中.

* 连接
  
  连接页面用来测试新配对的硬件设备,内嵌FastBLE模块

  <img style="width:22%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/task.png" align="center" /> <img style="width:22%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/data.png" align="center" /> <img style="width:22%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/tool.png" align="center" /> <img style="width:22%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/link.png" align="center" />

## 2.使用前准备
本软件通过蓝牙（BLE）与测量设备进行连接通信，使用测量功能前，需要先确保蓝牙能够顺利连接。
#### 2.1打开测量设备和手机蓝牙
首先，需要将蓝牙发射器插入测量设备，并将测量设备和蓝牙发射器都打开。

<img style="width:45%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/put_bluetooth.png" align="center" />  
<img style="width:45%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/open_ruler.png" align="center" />

图 5 插入蓝牙发射器并打开设备


之后，打开手机设置界面，将手机的蓝牙功能打开。

<img style="width:300px" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/open_bluetooth.png" align="center" />

图6 打开手机蓝牙功能

#### 2.2打开软件相关权限

为了使软件正常工作，建议安装时，或者安装之后先设置好软件必要的权限。下面列出软件运行中涉及到的权限及其用途
* 蓝牙和定位权限    蓝牙连接
* 文件读取权限      保存和读取数据文件
* 相机权限          拍摄照片
* 应用内安装软件    更新软件
* 读取机器识别码    识别设备,验证连接

<img style="width:30%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/app_setting.png" align="center" />  
<img style="width:30%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/app_permission.png" align="center" />


#### 2.3连接设备
完成上述准备工作之后，即可开启软件，点击连接设置，进入连接设置页面。点击页面下方，重新连接按钮，等待10s左右，软件弹出连接成功或者连失败。

## 3.产品管理
本软件的核心在于通过建立产品模板,用户即可通过测量向导,通过测量设备自动完成零件的测量和记录任务.

产品管理包括新建，删除，编辑，查看等。直接选中对应的项，点击按钮即可。长按产品项将其设置为当前产品,供测量向导使用.

<img style="width:30%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/product_manager.png" align="center" /> <img style="width:30%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/product_delete.png" align="center" />

产品管理页面（右侧为删除状态）


### 3.1新建/编辑

<img style="width:30%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/product_new.png" align="center" /> <img style="width:30%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/product_edit.png" align="center" />

新建/编辑产品

<img style="width:30%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/item_new.png" align="center" /> <img style="width:30%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/item_delete.png" align="center" />

新建/编辑测量项

### 3.2从Excel导入
为方便用户更快更准确的建立产品模板,软件提供了从Excel表格导入产品模板的功能,用户可预先在电脑上编辑好文件,传输到手机上,进行一键导入.

<img style="width:30%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/import_excel.png" align="center" /> <img style="width:30%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/choose_file.png" align="center" /> <img style="width:30%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/import_result.png" align="center" />


## 4.测量
按照使用游标卡尺的方法正常测量尺寸，确定之后，按下蓝牙发生器上的按钮，则数据往外传输，建立连接的软件端即接收到数据并进行处理（显示）。
#### 4.1自由测量
连接完成之后，即可进入通过主页面，点击自由测量，进入自由测量页面。滑动游标卡尺,按一下蓝牙发射器上的按钮,等待数秒,软件会提示接收到数据,并将其显示到页面上.

<img style="width:30%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/free.png" align="center" /> <img style="width:30%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/free_data.png" align="center" />

自由测量页面（右图为实际测量示例）

#### 4.2测量向导
根据实际需求，软件提供了测量向导的功能，用户可预先定义好需要进行测量检验的产品，之后便可按照产品中定义的顺序、测量项类型、尺寸要求等进行测量检验，完成之后生成测量结果。

<img style="width:30%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/wazarid_item.png" align="center" /> <img style="width:30%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/wazarid_info.png" align="center" />
  
测量向导（测量项，测量信息）

* 与自由测量类似,测量向导工作时也能接收蓝牙发射器发射过来的数据并自动填写为实测值.为保证兼容性,避免意外情况,实测值也支持直接点击输入.
* 点击当前项(绿色背景)的实际图三个字上方的图片,可根据需要附加图片到该测量项.
  
<img style="width:30%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/hand_edit.png" align="center" /> <img style="width:30%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/add_pic.png" align="center" />


## 5.导出结果
通过测量向导生成测量结果之后，需要再进行一步操作，生成报告。生成的报告为Excel格式，用户可直接在手机上用其他应用查看，或者进行分享，也可连接电脑进行拷贝和同步。

<img style="width:30%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/result_list.png" align="center" />

测量历史记录页面

导出报告时，需要一些预定义的信息，暂时将其放置到信息设置页面，后期考虑增加用户功能。

<img style="width:30%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/info.png" align="center" />

信息设置页面


#### 5.1生成报告
首先，在首页上点击历史记录，进入历史记录页面。滑动列表，选中测量结果，点击生成报告，即生成Excel报告。
    
<img style="width:30%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/result_detail.png" align="center" /> <img style="width:30%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/share_report.png" align="center" />

选中记录，点击导出Excel

<img style="width:30%" src="https://raw.githubusercontent.com/cy15196/ClabsoHandBooks/master/Handbook/img/report_temp.png" align="center" />

Excel报告样例（WPS打开）



### 联系我们
info@clabso.com
