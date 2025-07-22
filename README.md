
# RunFilesBuilder 


>> 这是一个工作流。同步各位大佬项目里最新编译的ipk文件 生成适用于iStoreOS/OpenWrt 用的run自解压包<br>
>> 本质上是利用makeslef,将ipk和shell文件打包成自解压程序。<br>
>> iStoreOS 可以在iStore商店手动安装<br>
>> ImmortalWrt或者其他OpenWrt 可下载后 使用 `sh xxx.run `来安装<br>
>> 使用 `sh xxx.run --target dir --noexec ` 只解压到dir目录 不执行安装
> <img src="https://github.com/user-attachments/assets/3f5dabba-1efa-4e67-bf5b-86a27c114902" height=40>




## run文件安装方法
## Install by iStore 
<img src=https://camo.githubusercontent.com/0a783d7ece59c727a1eef024855606c2b87be6acec14192e8103cf8c601d44eb/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f41554b393532372f4172652d752d6f6b406d61737465722f617070732f696e7374616c6c2e706e67>


## Install By Command
> Like This (Immortalwrt 等其他OpenWrt)
```bash
wget -O xxx.run <run下载地址>
sh xxx.run
```

## Immortalwrt 如何安装iStore商店
```
wget -qO imm.sh https://cafe.cpolar.top/wkdaily/zero3/raw/branch/main/zero3/imm.sh && chmod +x imm.sh && ./imm.sh

```


<details>
<summary><h2>🍭鸣谢和引用的项目 👇🏿</h2></summary>
  
> 【打包】https://github.com/megastep/makeself
> > 【引用】https://github.com/xiaorouji/openwrt-passwall<br>
> > 【引用】https://github.com/xiaorouji/openwrt-passwall2<br>
> > 【引用】https://github.com/vernesong/OpenClash<br>
> > 【引用】https://dl.openwrt.ai<br>
> > 【引用】https://github.com/morytyann/OpenWrt-mihomo/wiki<br>
> > 【引用】https://github.com/AdguardTeam/AdGuardHome/releases/latest<br>
> > 【引用】https://github.com/sbwml/luci-app-mosdns<br>
> > 【引用】https://downloads.immortalwrt.org


