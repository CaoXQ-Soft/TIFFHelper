# TIFFHelper/三味书屋多页TIFF软件

## 一、软件简介

三味书屋多页TIFF软件是一款社区性质的免费TIFF软件，主要专注于TIFF文件的处理，包括TIFF合并、TIFF拆分、TIFF调整、TIFF统计、TIFF压缩、分辨率检测、颜色检测，以及TIFF查看与编辑功能。

![image](https://github.com/user-attachments/assets/c929dfb6-6232-421c-9044-f59a9a2039b8)

## 二、下载地址
        GitHub：安装文件目录直接下载  
        中国大陆：  
            链接：https://pan.baidu.com/s/1sQ7etC3JT-VmpOJ79assDg?pwd=3u2e   
            提取码：3u2e  
            
## 三、更新说明（最新为7.0 版本）
        （1）TIFF文件的压缩方案调整，现在可以采用JPEG的压缩方式；  
        （2）任务栏进度指示器更新，现在可以通过任务栏预览任务执行进度。  
## 四、运行环境
        操作系统：Windows 64位   
        版本支持：Windows 7 / 8 / 8.1 / 10 / 11  
        注意事项：Windows 7 需升级SP1，并且需要安装补丁：KB3063858  

## 五、功能说明

### 5.1 TIFF查看与编辑
        提供一些常用的查看与编辑功能。  
        
        注意事项：   
        ① 支持打开的最大单个TIFF文件大小为 64GB ；   
        ② 支持打开的TIFF文件最大单帧尺寸为 65535 × 65535 。  
        
### 5.2 TIFF合并
        将jpg、bmp、png、tiff等图像合并成多页TIFF文件。  
        
        参数说明：  
        （1）合并方式：  
                ① 将每个子文件夹合并成一个TIFF文件；
                ② 将所有图像合并成一个TIFF文件。
        （2）压缩方案： 
                ① JPEG：使用 JPEG（联合摄影专家组）压缩方案；
                ② LZW：使用 LZW (Lempel-Ziv & Welch) 压缩方案； 
                ③ PackBits：使用 PackBits (Macintosh RLE) 压缩方案；
                ④ CCITT1D：使用 CCITT modified Huffman RLE 压缩方案；
                ⑤ Group3Fax：使用 CCITT Group 3 Fax 压缩方案；
                ⑥ Group4Fax：使用 CCITT Group 4 Fax 压缩方案；
                ⑦ Uncompressed：不使用压缩方案。
                注意：CCITT1D、Group3Fax 和 Group4Fax会自动将要合并的图像转换为黑白（BlackWhite）像素格式。

### 5.3 TIFF拆分
        将多页TIFF文件拆分成 jpg、bmp、png、tiff等格式。  

	参数说明：  
	        1、拆分方式： 
	                ① 每个TIFF文件拆分成一个单独文件夹；
	                ② 所有TIFF文件拆分至同一个文件夹。
	        2、保存格式： 
	                JPG、BMP、PNG、TIFF
	        3、JPG质量（当保存格式为JPG时可设置） 
	        4、隔行扫描（当保存格式为PNG时可设置）
	                ① Default：自动选择是否应该对图像进行隔行扫描；
	                ② On：对生成的位图图像进行隔行扫描；
	                ③ Off：不对生成的位图图像进行隔行扫描。
	        5、压缩类型（当保存格式为TIFF时可设置）
	                ① JPEG：使用 JPEG（联合摄影专家组）压缩方案；
	                ② LZW：使用 LZW (Lempel-Ziv & Welch) 压缩方案； 
	                ③ PackBits：使用 PackBits (Macintosh RLE) 压缩方案；
	                ④ CCITT1D：使用 CCITT modified Huffman RLE 压缩方案；
	                ⑤ Group3Fax：使用 CCITT Group 3 Fax 压缩方案；
	                ⑥ Group4Fax：使用 CCITT Group 4 Fax 压缩方案；
	                ⑦ Uncompressed：不使用压缩方案。
	                注意：CCITT1D、Group3Fax 和 Group4Fax会自动将要合并的图像转换为黑白（BlackWhite）像素格式。
	        5、命名格式
	                可以选择是否保留原始文件名并作为拆分文件名前缀
	        6、分隔符号（当勾选命名格式时可设置） 
	                可以选择或输入符号以将其用作分隔原始文件名的符号。
	        7、是否补零
	                可以选择是否对拆分的文件名进行补零，
	                例如：未选择此选项时，拆分文件命名格式为1.jpg，2.jpg……9.jpg等，如果选择此选项，则拆分文件命名格式为0001.jpg，0002.jpg……0009.jpg等。 
	        8、补零长度（当选择补零可设置）
	                补零长度可设置为3~8位，注意：当拆分的文件顺序号大于所设置的补零长度时，将不会补零，而是保留原有顺序名称。
                例如：当设置补零长度为3位时，但有一份多页TIFF文件有1001帧图像，那么拆分后的第1000帧图像和第1001帧图像的命名是1000.jpg、1001.jpg。

### 5.4 TIFF调整
        可以对多页TIFF文件进行逐帧缩放、DPI更改、像素格式更改等。

	参数说明：
	        1、启用缩放：
	                对TIFF文件启用缩放操作； 
	        2、缩放模式： 
	                ① 保持缩放纵横比 
	                ② 自定义宽度和高度的缩放比例
	        3、缩放比例 
	                可以选择或输入1~100%的缩放比例，默认为85%。 
	        4、DPI更改
	                对TIFF文件启用DPI更改操作；
	        5、DPI模式 
	                ① 保持DPI纵横比
	                ② 自定义宽度和高度的DPI
	        6、DPI数值： 
	                可以选择预定义或输入自定义的DPI数值。 
	        7、像素格式 
	                对TIFF文件启用像素格式更改操作；
	        8、像素格式
			https://learn.microsoft.com/zh-cn/dotnet/api/system.windows.media.pixelformats?view=windowsdesktop-6.0&devlangs=csharp&f1url=%3FappId%3DDev16IDEF1%26l%3DZH-CN%26k%3Dk(System.Windows.Media.PixelFormats)%3Bk(DevLang-csharp)%26rd%3Dtrue
	        9、调色板格式（仅当像素格式为Indexed索引系列时可选） 
			https://learn.microsoft.com/zh-cn/dotnet/api/system.windows.media.imaging.bitmappalettes?view=windowsdesktop-8.0
	        10、保存方式 
	                ① 保存并替换原文件
                ② 另存为新文件（保留文件夹结构）![image](https://github.com/user-attachments/assets/bd466f50-3aa5-4f15-ba3e-779e8594cd63)

### 5.5 TIFF统计
        可以对多页TIFF文件的帧数进行统计，并导出为Excel表。
        注意：当TIFF统计的份数超过Excel行数限制（1048576）时，导出Excel时会自动对Excel文件进行分割，例如：当TIFF总份数为200万时，此时导出的Excel会自动分割为两份Excel文件。

### 5.6 TIFF压缩
        可以对多页TIFF文件进行压缩，以减少文件体积，并支持将压缩结果导出为Excel表。
            注意：当TIFF统计的份数超过Excel行数限制（1048576）时，导出Excel时会自动对Excel文件进行分割，例如：当TIFF总份数为200万时，此时导出的Excel会自动分割为两份Excel文件。

	参数说明：
	        1、压缩方案 
	                ① JPEG：使用 JPEG（联合摄影专家组）压缩方案；
	                ② LZW：使用 LZW (Lempel-Ziv & Welch) 压缩方案； 
	                ③ PackBits：使用 PackBits (Macintosh RLE) 压缩方案；
	                ④ CCITT1D：使用 CCITT modified Huffman RLE 压缩方案；
	                ⑤ Group3Fax：使用 CCITT Group 3 Fax 压缩方案；
	                ⑥ Group4Fax：使用 CCITT Group 4 Fax 压缩方案；
	                ⑦ Uncompressed：不使用压缩方案。
	                注意：CCITT1D、Group3Fax 和 Group4Fax会自动将要合并的图像转换为黑白（BlackWhite）像素格式。
	        2、保存方式 
	                ① 保存并替换原文件
                ② 另存为新文件（保留文件夹结构）

### 5.7 TIFF分辨率检测
        可以对多页TIFF文件的分辨率进行逐帧检测，并导出为Excel表。
        注意：当TIFF检测的帧数超过Excel行数限制（1048576）时，导出Excel时会自动对Excel文件进行分割，例如：当TIFF总帧数为200万时，此时导出的Excel会自动分割为两份Excel文件。

        参数说明： 
                1、检测DPI： 
                        可以选择或输入用作参照标准的DPI。 
                2、检测条件： 
                        可以选择大于、等于、小于的比较条件。

### 5.8 颜色检测
        可以对多页TIFF文件的颜色类型进行逐帧检测，并导出为Excel表。
        注意：当TIFF检测的帧数超过Excel行数限制（1048576）时，导出Excel时会自动对Excel文件进行分割，例如：当TIFF总帧数为200万时，此时导出的Excel会自动分割为两份Excel文件。


        参数说明：
                1、检测模式： 
                        ① 依据像素格式检测
                        ② 依据图像内容检测
                2、检测颜色 
                        可以选择彩色、灰度、黑白； 
                3、模糊匹配（当检测模式为“依据图像内容检测”时可选） 
                        是否启用黑白颜色模糊匹配，当启用该选项后，黑白颜色的RGB判断值将由                            （0，255）改为（0~30，230~255） 
                4、检测条件 
                        可以选择等于或不等于。

## 六、关于
        可以在这里了解到软件的一些附加信息，以及如何寻求帮助。



