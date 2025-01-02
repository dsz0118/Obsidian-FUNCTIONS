# TODO

- #TODO 表待办，方便检索文件中需要处理的部分，仅放在 <b><i><font  color = #FF0000 >文档内容</font></i></b> 中

## TODO/

- #TODO/complete 表示此处需要完善
- #TODO/understand 表示此处有待理解

---
# STATE

- #STATE 属于文件的“状态量”，仅能放在<b><i><font  color = #FF0000 >开头</font></i></b>

## STATE/

- #STATEONHOLD 表示该文档由于特殊情况处于暂时中断，等待后续处理，并非彻底完成
- #STATE/UNDERWAY 表示该文档处于进行中，便于检索
- #STATE/UPDATING 表示该文档曾今已完成，如今需要更新

---
# PLUGINS

- #PLUGINS 属于插件的专用标签，方便插件特殊功能使用

- #PLUGINS/cloze 用于 `Cloze` 插件的使用

---
# \*Rules

1. 优先使用已经存在的标签名
	- eg： 
		- #todo ❌ 
		- #TODO/improve ✅
2. 多单词仅使用 `-` 作为连词符
3. `状态类` 大写，`动作类`小写
	- eg :
		- #STATE/UPDATING 表示文档需要更新
		- #TODO/improve 表示此处的内容有待完善