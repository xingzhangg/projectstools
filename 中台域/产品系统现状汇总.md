# **OYO架构治理-系统架构**

---


|版本|时间|编写人|备注|
|:----|:----|:----|:----|
|V1.0|2020.09.23|袁文科|    |
|V1.1|    |    |    |


# 0000、总图

## 产品功能地图：

![图片](https://uploader.shimo.im/f/LQbptxXPEScHfVW8.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 应用协同地图：

![图片](https://uploader.shimo.im/f/FR4T7CWwEnFZbx9h.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


## 公司核心一级业务流程

签约/重签/解约

[https://www.processon.com/view/link/5f6c6ea37d9c08039fb80542](https://www.processon.com/view/link/5f6c6ea37d9c08039fb80542)

定价

酒店服务商品上线

[https://www.processon.com/view/link/5ecc90525653bb79c1ff89a1](https://www.processon.com/view/link/5ecc90525653bb79c1ff89a1)


酒店服务商品下线

用户预订

用户入住

用户离店

发布营销活动

会员邀请会员

前台推荐入会员

发布账单


![图片](https://uploader.shimo.im/f/3apkYJ4cEECT6ks6.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/SaVQRDcyo78v0NZ4.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 
# 1001、C端APP

## 产品功能图

![图片](https://uploader.shimo.im/f/gjEpngMCbveGhUe6.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


1、模糊搜索（搜索建议）：在城市列表页、酒店列表页分场景推荐建议词

2、酒店列表页：通过距离、POI、价格等筛选酒店，综合排序

3、酒店详情页：原csa-biz中的详情页的聚合逻辑迁移至shopping-guide

3、首页热门酒店、附近酒店推荐

4、首页热门城市推荐：根据用户搜索过的城市、住过的酒店所在城市、距离定位等推荐热门城市

5、城市列表页

6、城市POI页：点击首页城市进入该城市热门POI列表

## 业务流程图

常用功能业务流程图

![图片](https://uploader.shimo.im/f/Vqqw5WsbE2HRlw6v.jpg!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

城市接口

![图片](https://uploader.shimo.im/f/48bsoIv1BwAeEwzh.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

模糊搜索

![图片](https://uploader.shimo.im/f/Nypd0JDjeqTYN0Et.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

酒店列表

![图片](https://uploader.shimo.im/f/6RXdyzMtn06LZ1GM.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

酒店详情

![图片](https://uploader.shimo.im/f/kYhAj30UHMlxKMA1.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

价格策略

![图片](https://uploader.shimo.im/f/4JhIMNsPhKvqWigC.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 系统用例图


## 系统集成关系图

![图片](https://uploader.shimo.im/f/auK93i9hbegrALtD.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 应用部署架构图

# **1003、遨游通（TMC）**

## 产品功能图

![图片](https://uploader.shimo.im/f/aeDaJZaA5TE5NjSt.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 业务流程图

### 【CRM】新建客户/配置

![图片](https://uploader.shimo.im/f/KOaTsIVhibsb2EQd.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

### 【遨游通】正向支付（分期支付）

![图片](https://uploader.shimo.im/f/mgGHJaFu1DE2LB67.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

### 【遨游通】正向支付（全额支付）

![图片](https://uploader.shimo.im/f/GKz3VJ9fsiEXDP78.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

### 【遨游通】逆向退款（全额支付）

![图片](https://uploader.shimo.im/f/mXu5fYfqmhMeJTJC.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

### 【遨游通】库存处理

![图片](https://uploader.shimo.im/f/c99tOkhEu8ArOmWk.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

【遨游通】延期尾款支付

![图片](https://uploader.shimo.im/f/sscS0Y2CTzc3UmqH.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

### 【PMS】支付

![图片](https://uploader.shimo.im/f/XAnKNju2pRIlMZUy.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

### 【客服】申诉退款

![图片](https://uploader.shimo.im/f/IEN0efCrJ5gB6xsH.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 系统用例图

![图片](https://uploader.shimo.im/f/fNuF7mKoiAXSq4LL.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 系统集成关系图

![图片](https://uploader.shimo.im/f/5VVRiGPStRPc7wft.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 应用部署架构图

# 1007、Flash APP

## 产品功能图

![图片](https://uploader.shimo.im/f/VHi3SpKcKy9XNRdF.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/aogGQNuZsyWPEORl.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


## 业务流程图

**根据规则触发相关任务**

**——**ABM需在规定时间内完成，一旦完成将顺利进入后续流程/展示结果或对比数据

**——**如未完成，Flash会将任务完成情况通知ABH/&CGM，且计入ABM/ABH的KPI。

——部分过期未完成任务将重复发送，直至ABM完成为止

![图片](https://uploader.shimo.im/f/RNYseH2bkaUi69WI.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 系统用例图

![图片](https://uploader.shimo.im/f/sEj5PXVQww7JgO1x.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


## 系统集成关系图

* 后台管理

![图片](https://uploader.shimo.im/f/vmkbIrnng499To9i.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

* FlashAPP

![图片](https://uploader.shimo.im/f/9NKe0IiE7qKecg5c.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


![图片](https://uploader.shimo.im/f/I702Hv6XuYbJUfZK.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)



## 应用部署架构图


# 1011、CRM

## 产品功能图

![图片](https://uploader.shimo.im/f/93cvwmXAaw74ewOp.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


## 业务流程图

![图片](https://uploader.shimo.im/f/Q7yK1dWSihglG80j.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 系统用例图

![图片](https://uploader.shimo.im/f/rq7oOrsjQPnQ8DYz.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/sSCNingwcKUwmZzT.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 系统集成关系图

![图片](https://uploader.shimo.im/f/xIkK1fsr3oZpMJIh.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


## 应用部署架构图

# 1013、OTA小渠道

## 产品功能图

![图片](https://uploader.shimo.im/f/bU2JSNLJic6ZbINi.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


## 业务流程图

![图片](https://uploader.shimo.im/f/AnLREYeWSZcRQfPB.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/i1cQfN6lqK3LrbFe.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/9BdNisTXFRLKDvNa.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/64mSxM0P1EodzIKW.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/vEK5QJdEEoCK8ynJ.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/3BVWK2vrXZg4CR2K.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/q8JNc9oaBqKnjbp0.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/IeqOWFdfRBlxT5qt.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 

## 系统用例图


## 系统集成关系图

![图片](https://uploader.shimo.im/f/UUQzdf7giL54Lx7e.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


## 应用部署架构图



# 1026、财务结算

## 产品功能图

![图片](https://uploader.shimo.im/f/MS1tX52XI80cHBoa.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/6riVkDEOOJ81aoBS.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 业务流程图

![图片](https://uploader.shimo.im/f/jmCKETcEBkOvNfRW.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)




## 系统用例图

![图片](https://uploader.shimo.im/f/RAtYHBeHyb9mlDj5.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


## 系统集成关系图

![图片](https://uploader.shimo.im/f/PHNSmVSWe7yZ16JI.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 应用部署架构图

![图片](https://uploader.shimo.im/f/gqp84BmflC1WzJ5D.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

owner账单展示：

![图片](https://uploader.shimo.im/f/WeQD5GLADI9Fgqhz.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

# 1024、供应链scm

## 产品功能图

![图片](https://uploader.shimo.im/f/bazv3DUPEaE3ghF2.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/6sNt5xZyBImZYDlY.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


## 业务流程图

![图片](https://uploader.shimo.im/f/e8kmKjnlzD2nCqyN.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/0z0Vpie0b5aCROlF.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## ![图片](https://uploader.shimo.im/f/EkVmdROXGfDblqpe.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 系统用例图


## 系统集成关系图




## 应用部署架构图

# 
## 


# 1025、支付

## 产品功能图

![图片](https://uploader.shimo.im/f/1YCdIcsD2df1lD9t.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 业务流程图

![图片](https://uploader.shimo.im/f/JRPxGtK8ybz14iLX.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)






## 系统用例图

![图片](https://uploader.shimo.im/f/2gkqIV2tGUGuOsH7.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 系统集成关系图

![图片](https://uploader.shimo.im/f/C8D9kow8DIB4d0Qf.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)



## 应用部署架构图

# ![图片](https://uploader.shimo.im/f/xCL9DF25U6wdulnr.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

# 
# 1027、财务预算

## 产品功能图

![图片](https://uploader.shimo.im/f/1EHMuqFIRoQJ2Vmo.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 业务流程图

![图片](https://uploader.shimo.im/f/xCemziZJ7qUNKTOp.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


## 系统用例图

![图片](https://uploader.shimo.im/f/GV0giqmKEhd6Jzbv.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


## 系统集成关系图

![图片](https://uploader.shimo.im/f/4RwVKBYCYLDlv5ZI.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)




## 应用部署架构图

![图片](https://uploader.shimo.im/f/2FndKckfvYuC8Uy7.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)



# 1028、资金账户

## 产品功能图

![图片](https://uploader.shimo.im/f/qtlVBZOcuzXKB2vC.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 业务流程图


## 系统用例图

![图片](https://uploader.shimo.im/f/2TlN1dlHnJWOqA8e.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)



## 系统集成关系图

![图片](https://uploader.shimo.im/f/mUhJsZJNM08fqiT4.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)





## 应用部署架构图

![图片](https://uploader.shimo.im/f/gp2fCRaVHF7BEiEW.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

# 1004、OwnerApp

## 产品功能图

![图片](https://uploader.shimo.im/f/e3FHF5fxVY6YSExX.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


## 业务流程图

![图片](https://uploader.shimo.im/f/SSKeI4WVXvqfL2yW.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/gF0g8VDeKi8ewS1U.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


## 系统用例图

![图片](https://uploader.shimo.im/f/F4Ec1HGYa5tgiMRs.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


## 系统集成关系图

![图片](https://uploader.shimo.im/f/VHtOIE4EdKKfCVlh.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)



## 应用部署架构图

![图片](https://uploader.shimo.im/f/JBeMEqRwxjdacLxi.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


# 1005、PMS

## 产品功能图

![图片](https://uploader.shimo.im/f/0RLHRU9PjoKl1dOI.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


## 业务流程图


## 系统用例图

pms

![图片](https://uploader.shimo.im/f/gMRnsmU0GB5AdCn9.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


定时任务

![图片](https://uploader.shimo.im/f/HqstH4uOsgWb6rR6.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

智能硬件/门锁

![图片](https://uploader.shimo.im/f/Q3beIHJCcAs4fF0G.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


## 系统集成关系图

门店

![图片](https://uploader.shimo.im/f/ViAmWebSYNEFatFD.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

智能门锁

![图片](https://uploader.shimo.im/f/77JyndrqqsRKuM7G.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 应用部署架构图

# 1006、阿波罗系统

## 产品功能图

![图片](https://uploader.shimo.im/f/WmaQrLN9Bdm5Rpkk.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/8xMVlVAPIL632Mhm.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 业务流程图

[https://www.processon.com/view/link/5f6c6ea37d9c08039fb80542](https://www.processon.com/view/link/5f6c6ea37d9c08039fb80542)

## 系统用例图

![图片](https://uploader.shimo.im/f/Bsk45H84qLrT9nK2.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 系统集成关系图

## ![图片](https://uploader.shimo.im/f/VbTqMGm8FUIOOwjo.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 应用部署架构图




# 1022、协议后台管理

## 产品功能图

![图片](https://uploader.shimo.im/f/Jf208W8i0kWVX9mE.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/YClyjP5GjmjEh4pq.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


## 业务流程图

![图片](https://uploader.shimo.im/f/cEyQUD1mB4k0TpzN.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/YXrTlgsEMVXxpOEw.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)



## 系统用例图

![图片](https://uploader.shimo.im/f/iKC3jk0rUyNTGQES.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)



## 系统集成关系图

![图片](https://uploader.shimo.im/f/PKQgJsGiHrjUmYj1.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)



## 应用部署架构图

# ![图片](https://uploader.shimo.im/f/0v0F83q3TdizbSN1.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

# 
# 1016、申诉审计平台

## 产品功能图

![图片](https://uploader.shimo.im/f/sU7sWQg2gqw7r300.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 业务流程图

![图片](https://uploader.shimo.im/f/EFgc9w7hREzqmRCp.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 系统用例图

1. 申诉

![图片](https://uploader.shimo.im/f/bKi58xPXkQZjNbdy.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

2. 审计后管

![图片](https://uploader.shimo.im/f/A5E9cQJJm5ptr7jr.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 系统集成关系图

1. 申诉

![图片](https://uploader.shimo.im/f/P80HZLEeuBlQdk98.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)



## 应用部署架构图

![图片](https://uploader.shimo.im/f/Gfj38jkbeBJAxqs8.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

# 

# 1021、位置后台管理

## 产品功能图

![图片](https://uploader.shimo.im/f/cso65JwM5GchsyVi.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 业务流程图

![图片](https://uploader.shimo.im/f/vv5XvZXlJGwXUgoD.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)



## 系统用例图

![图片](https://uploader.shimo.im/f/wfRWm60TfSmurofi.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)



## 系统集成关系图

## 应用部署架构图

# ![图片](https://uploader.shimo.im/f/58ShpnHf3S0DR8VE.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

# 
# 

# 

# 1015、客服后台管理

## 产品功能图

![图片](https://uploader.shimo.im/f/p3kmT3pweZ0XiDhR.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/6l0a25YkH6HD2CjV.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)



## 业务流程图

![图片](https://uploader.shimo.im/f/da8Sh7Qy8E1EJrG3.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/ov7sColofCxDRCZY.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

业务记录生成

![图片](https://uploader.shimo.im/f/BFWvVZSq8R1Dvazi.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

录入工单

![图片](https://uploader.shimo.im/f/hBhpu6LqM3BDKOKE.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

领取工单：

![图片](https://uploader.shimo.im/f/VfAE13XnDfUQa3Ht.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

解决工单：

![图片](https://uploader.shimo.im/f/HmMGMJBx1UhcT8tb.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

关闭工单：

![图片](https://uploader.shimo.im/f/Rit0FuLgCUxA1xQ2.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 系统用例图


![图片](https://uploader.shimo.im/f/5kitntAft5w3B6lE.jpg!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/voYuE7nvtfkBDAfG.jpg!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 系统集成关系图

![图片](https://uploader.shimo.im/f/QLYq0vPSqLu635CP.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 应用部署架构图

# 1009、营销平台

## 产品功能图

![图片](https://uploader.shimo.im/f/AoKCiXS5G79ZD7NS.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 业务流程图

![图片](https://uploader.shimo.im/f/NAGYSSQvRD7EA6lo.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


## 系统用例图

![图片](https://uploader.shimo.im/f/F9gLmipq8sQEAipG.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)![图片](https://uploader.shimo.im/f/DSq6MJTqXtYgUKd5.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)![图片](https://uploader.shimo.im/f/3f2fEZwq86UXTd0P.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)![图片](https://uploader.shimo.im/f/MEBwCL7cFPUjX4Zh.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)![图片](https://uploader.shimo.im/f/kRqXTIxSJeA9D0MV.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)![图片](https://uploader.shimo.im/f/jql8b2V9tdoYa5V3.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 系统集成关系图

![图片](https://uploader.shimo.im/f/iPzg8DMt8wYhVK6w.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/DVSjVMRupeg9gzBU.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/Reb1RWO6S7Mb4OR4.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 应用部署架构图

# 1010、筋斗云

## 产品功能图

![图片](https://uploader.shimo.im/f/BM6pkw6DohqdA9pi.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 业务流程图

![图片](https://uploader.shimo.im/f/0clQKz92GVsdsiQy.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 系统用例图

## 系统集成关系图

## 应用部署架构图

# 1012、CMS

## 产品功能图

## 老CMS

![图片](https://uploader.shimo.im/f/qy3c7dnFDI8bNJPi.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 新CMS

![图片](https://uploader.shimo.im/f/z0rz4frJjtQbt6vA.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


## 业务流程图


## 系统用例图

![图片](https://uploader.shimo.im/f/pHy2F4joXOORPf7G.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)



## 系统集成关系图


## 应用部署架构图

# ![图片](https://uploader.shimo.im/f/essxY4SVno8JuvYf.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

# 1028、SRM采购系统

## 产品功能图

![图片](https://uploader.shimo.im/f/Uj4J4mgdZ9iLhmVD.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 业务流程图

![图片](https://uploader.shimo.im/f/4QDa8EkH4BImr6mY.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)



## 系统用例图

![图片](https://uploader.shimo.im/f/s3Yy5CGfMMEoH4qy.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)



## 系统集成关系图

![图片](https://uploader.shimo.im/f/vEggmin0Mbc488h2.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 应用部署架构图

# ![图片](https://uploader.shimo.im/f/1auZFqYoPjhCevnH.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

# 
# 1029、财务费控(HEC)

## 产品功能图

![图片](https://uploader.shimo.im/f/aVscq1vdLYvzhUTo.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

目前系统功能业务只涉及到费用管理，财务作业平台和结算平台

![图片](https://uploader.shimo.im/f/qPJGwDm5PNFAAyHg.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)



## 业务流程图

![图片](https://uploader.shimo.im/f/JCc3Ke2BZ485yPVQ.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/GoXx2dMYHWGkM68b.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/wBsoZia4gcudM6rW.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/abusxHD0NNlDrulG.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)



## 系统用例图

![图片](https://uploader.shimo.im/f/ot9op8S2fULVoZJA.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)




## 系统集成关系图


![图片](https://uploader.shimo.im/f/pLA5DXslEYWZ64vD.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)





## 应用部署架构图

![图片](https://uploader.shimo.im/f/DRjk38xKSXQPH5wk.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


# 1030、财务EBS系统

## 产品功能图

![图片](https://uploader.shimo.im/f/wh7WTvYalSQGwnxy.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


## 业务流程图

![图片](https://uploader.shimo.im/f/gavd4BMMufwFkpy2.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/VGqSWK4ueeSwUCSZ.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 系统用例图


## 系统集成关系图


## 应用部署架构图

![图片](https://uploader.shimo.im/f/x974C8S0LzT0oASG.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)



# 1014、控价系统

## 产品功能图

![图片](https://uploader.shimo.im/f/zmNQ3kh4hRJOo4IR.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


## 业务流程图

![图片](https://uploader.shimo.im/f/RSwK8RI3hbUMwyM1.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


## 系统用例图


## 系统集成关系图

![图片](https://uploader.shimo.im/f/hiy5tFKTXmEW0Vn2.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 应用部署架构图

![图片](https://uploader.shimo.im/f/MBZFRuSxRgTce5md.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)



# 1031、算法推荐

## 产品功能图



## 业务流程图

![图片](https://uploader.shimo.im/f/qxO2fODHwimxkSU7.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 系统用例图


## 系统集成关系图


## 应用部署架构图

# 1032、算法选店




# 1033、算法增长

## 产品功能图

![图片](https://uploader.shimo.im/f/3m1IkelAEUYAGJmm.jpg!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 业务流程图

![图片](https://uploader.shimo.im/f/NKgeALppVvMbSPio.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


## 系统用例图


## 系统集成关系图


## 应用部署架构图

TODO


MAPI Client: 10.203.3.134

ETL: HERA

supertset:10.203.3.134

Tabelau:

# 1034、算法风控

## 产品功能图

TODO

## 业务流程图

TODO

## 应用部署架构图

TODO


# 1035、价格引擎

## 产品功能图


## 业务流程图

![图片](https://uploader.shimo.im/f/v7P2JtwZvLasCIMV.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

### 3.0 价格计算流程

![图片](https://uploader.shimo.im/f/fCR5oWLjnigma8nI.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 系统用例图


## 系统集成关系图

![图片](https://uploader.shimo.im/f/D2QaJn1CiYnod74T.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 应用部署架构图

![图片](https://uploader.shimo.im/f/MAneG5dogFJ9Knjp.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)



# 1017、用户中心

## 产品功能图

![图片](https://uploader.shimo.im/f/BtWKizqAl4xWji2A.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/cN9D3XDFDudnLfqc.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/I1FjTWldoavaEAij.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/Db9x6m1GgBbPNr8p.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/jltWVd1dOPEwetjW.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/d92AdD7jqGvsHXY3.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/zueloGAbl2kbhaEO.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/1rsahwuBmg8q6bbf.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/PUisvyNqmolbaaih.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/PyXfrebGeSU9zqSP.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/K4iwWQNz2RrXikCz.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/dkJ83QZ5Ayi23pP5.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


## 业务流程图

![图片](https://uploader.shimo.im/f/86FFb3DVZJH6P8ud.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/YD4jtNWMed1nEhU8.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/1ix4uGNHZmVsUFMl.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/lboVEf2k1QMmqawp.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)




## 系统用例图

![图片](https://uploader.shimo.im/f/0aZZmo2SUYsTbGDq.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/rm3eD2PQq0mG3OB9.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/T0jfhirGiM7JGVai.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/kmtV9KYRRUD1Fgew.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


## 系统集成关系图

![图片](https://uploader.shimo.im/f/kkOrYFQA84TsHg3H.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 

## 用户中心逻辑架构图

![图片](https://uploader.shimo.im/f/FtxNXioEFgAmXvWj.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 应用部署架构图

# 1018、商品中心

## 产品功能图

![图片](https://uploader.shimo.im/f/OdUvrU0re1ZuApMh.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/iZ3XObp1ABNgfZrn.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 业务流程图

![图片](https://uploader.shimo.im/f/0Xab93KtIbbnGZUD.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/56xnJlaPV1XsLRky.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/Ge07OSuOJYKQAy8m.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 系统用例图

## ![图片](https://uploader.shimo.im/f/GJQKz0zoAywFqGFp.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 系统集成关系图

![图片](https://uploader.shimo.im/f/kkOrYFQA84TsHg3H.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 应用部署架构图

![图片](https://uploader.shimo.im/f/RDgZH6MUBFE013VG.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

# 1018、评论中心

## 产品功能图

![图片](https://uploader.shimo.im/f/5oZxKgYOsSCI74yU.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 业务流程图


## 系统用例图

## 系统集成关系图

![图片](https://uploader.shimo.im/f/afAbRJcAG9ZYhcXA.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


## 应用部署架构


# 1044、网关

## 产品功能图

![图片](https://uploader.shimo.im/f/N3s6PHr9zEDScULh.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 
## 业务流程图

![图片](https://uploader.shimo.im/f/y907rEmHCyBfJAqn.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 
## 系统用例图

![图片](https://uploader.shimo.im/f/OTILjpaClMDtzoQV.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 
## 系统集成关系图

![图片](https://uploader.shimo.im/f/Ckp2AAL6hTre0MpU.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 
## 应用部署架构

![图片](https://uploader.shimo.im/f/j44dT2Uz101rjkV0.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


# 1035、爬虫

## 产品功能图

|**爬虫功能**|
|:----|
|百度OYO酒店-TRPS 爬取OYO酒店在百度上地址及经纬度信息|
|飞猪OYO酒店-EBK搬单，当天预订|
|飞猪OYO酒店-EBK补单 未来3天入住订单|
|美团全网酒店-酒店房型价格信息|
|美团全网酒店-酒店交通信息|
|美团全网酒店-酒店列表及详情信息|
|美团全网酒店-酒店详情信息|
|美团指定酒店-酒店房型价格信息|
|美团OYO酒店-EBK包房数据爬取|
|美团OYO酒店-酒店评分评论|
|美团OYO酒店-酒店图片信息|
|美团OYO酒店-酒店详情及房型价格信息|
|美团OYO酒店-美团搬单 当天预定|
|美团OYO酒店-APP的酒店详情、房型及价格信息|
|美团OYO酒店-ebk酒店分数信息|
|美团OYO酒店-ebk流量，基础评分信息|
|美团OYO酒店-EBK账号密码验证|
|美团OYO酒店-EBK账号自动登录|
|去哪儿OYO酒店-酒店评论信息|
|携程全网景点-景点详情信息|
|携程全网酒店-房型价格信息|
|携程全网酒店-酒店交通信息|
|携程全网酒店-酒店列表信息|
|携程全网酒店-酒店排名信息|
|携程全网酒店-酒店所属街道信息|
|携程全网酒店-酒店详情信息|
|携程全网酒店-酒店周边及同品牌酒店信息|
|携程全网酒店-酒店周边交通信息|
|携程指定城市景点-景点对应的门票信息|
|携程指定城市景点-景点对应的图片信息|
|携程指定酒店-酒店房型价格信息|
|携程OYO酒店-竞对酒店未来7天房型价格信息|
|携程OYO酒店-酒店评论信息|
|携程OYO酒店-酒店图片数量信息|
|携程OYO酒店-酒店图片信息|
|携程OYO酒店-酒店详情图片总数|
|携程OYO酒店-酒店详情信息，房价，评论信息|
|携程OYO酒店-携程搬单 过去14天入住|
|携程OYO酒店-携程搬单 未来三天入住|
|携程OYO酒店-携程搬单，当天预定|
|携程OYO酒店-携程自动登录 windows|
|携程OYO酒店-自动登录-linux|
|携程OYO酒店-active酒店房型价格信息|
|携程OYO酒店-EBK后台酒店电话信息|
|携程OYO酒店-EBK获取酒店及房型信息|
|携程OYO酒店-EBK竞对酒店信息|
|携程OYO酒店-EBK酒店诚信分信息|
|携程OYO酒店-EBK酒店处罚信息|
|携程OYO酒店-EBK酒店流量概览信息|
|携程OYO酒店-EBK酒店流量转化信息|
|携程OYO酒店-EBK酒店排名信息|
|携程OYO酒店-EBK酒店评分信息|
|携程OYO酒店-EBK酒店信息|
|携程OYO酒店-EBK酒店预定电话信息|
|携程OYO酒店-EBK月账单信息|
|携程OYO酒店-EBK周账单信息|
|艺龙OYO酒店-酒店评论信息|

## 业务流程图

![图片](https://uploader.shimo.im/f/WcFpDjPnEcInYzuv.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/CFOXAW0L414IR7ko.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


## 系统用例图

![图片](https://uploader.shimo.im/f/GDIDUGCgO5kfWaTe.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


## 系统集成关系图


![图片](https://uploader.shimo.im/f/9IhLU0kfBsBijde7.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)




## 应用部署架构图

![图片](https://uploader.shimo.im/f/u1HQ2oV5KlyaHf0z.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)





# 1036、大数据

## 产品功能图

大数据平台整体架构图

![图片](https://uploader.shimo.im/f/Npn2xDPIzSHT64T2.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

数据开发平台功能图

![图片](https://uploader.shimo.im/f/eiguZc5DOXgB1y5c.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)



## 业务流程图

埋点上报系统业务流程图

![图片](https://uploader.shimo.im/f/bDonsRDJMALDf8Kq.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


## 系统用例图

埋点上报系统用例图

![图片](https://uploader.shimo.im/f/cfaY5xJfrwhks5QY.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

spark On Yarn 实时计算系统用例图

![图片](https://uploader.shimo.im/f/F6wc2hkM4YWGM3zZ.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)



## 系统集成关系图

大数据平台系统集成关系图

![图片](https://uploader.shimo.im/f/tH7aQ9p56y1RDkP4.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


## 应用部署架构图

# 1041、发布平台

## 产品功能图

![图片](https://uploader.shimo.im/f/hMmZ31QaPFw6Zkz5.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

# 1042、运维平台

## 产品功能图

![图片](https://uploader.shimo.im/f/45eeJwN4sJ4gVD9N.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

# 1040、云效平台

# ![图片](https://uploader.shimo.im/f/wt8VfNzgQI9hpoHw.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


# 1043、监控平台

1. APM平台
    1. 功能架构

![图片](https://uploader.shimo.im/f/3W8YUaQ2dwIbEdoA.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

b.技术架构

![图片](https://uploader.shimo.im/f/eqF8Aw9JxftBuu9h.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

c. 领域模型

![图片](https://uploader.shimo.im/f/iZ2ZqbIzgnTn2HvH.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

d. 核心流程

![图片](https://uploader.shimo.im/f/X7VgbOrxMQJCUePt.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

plugin注册序列图

![图片](https://uploader.shimo.im/f/O1XKDSq3rsq3q1wn.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

组件增强序列图

![图片](https://uploader.shimo.im/f/1CNyplHcqKHMDFZd.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

调用数据生成（Dubbo服务消费方）

![图片](https://uploader.shimo.im/f/DDx1wyBk6N9RYYy5.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

调用数据生成（Dubbo服务提供方）

![图片](https://uploader.shimo.im/f/qHHaxBfmcurPup7t.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

调用数据生成（线程）

![图片](https://uploader.shimo.im/f/46Rj63XkEzDVJTR5.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

![图片](https://uploader.shimo.im/f/HS99WOQegWvCk7Qq.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


2. 告警中心

a. 逻辑架构

![图片](https://uploader.shimo.im/f/4Ten1nhfpuS2Z7hA.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

b. 部署架构

![图片](https://uploader.shimo.im/f/pnmyl3XCL6Kkh6oh.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

c. 领域模型

![图片](https://uploader.shimo.im/f/xY8YANDWeeBmkA29.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

d. 核心流程

![图片](https://uploader.shimo.im/f/wZFNnRTVAxW5RvCD.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

告警中心核心流程

![图片](https://uploader.shimo.im/f/7zOlU2J1nK8ANM4q.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

工单中心核心流程

# 1047、搜索管理平台

## 产品功能图

![图片](https://uploader.shimo.im/f/X6hPOFVbJQhD3MjZ.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 业务流程图

## 系统用例图

## 系统集成关系图

## 应用部署架构图

# 1020、规则中心

## 产品功能图

## 业务流程图

规则打包：

![图片](https://uploader.shimo.im/f/6tdiY5Z79MAh7BTw.jpg!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 系统用例图

![图片](https://uploader.shimo.im/f/OMmEtYBaOmvWqtSb.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 系统集成关系图

## 应用部署架构图

![图片](https://uploader.shimo.im/f/nR8fzUjR43JNlGJO.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

# 指标平台

## 产品功能图

![图片](https://uploader.shimo.im/f/RHJHvfjorQUNr1Qr.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


## 业务流程图

![图片](https://uploader.shimo.im/f/BgCLR2UedjDczAF8.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


## 系统用例图


## 系统集成关系图

![图片](https://uploader.shimo.im/f/Tc5vmJOYmIBSdSid.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

## 应用部署架构图

# 1045、工作流任务中心

## 产品功能图

![图片](https://uploader.shimo.im/f/n367e6q9RuPt8eeD.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)

web端功能

![图片](https://uploader.shimo.im/f/fmQPc4fCWHpCCM3y.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


## 业务流程图

## 系统用例图

## 系统集成关系图

![图片](https://uploader.shimo.im/f/xx9l2wAGiwRpd8gA.png!thumbnail?fileGuid=oR1z9egkDC4mwM0J)


