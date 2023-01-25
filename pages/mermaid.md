- mermaid的文档[https://mermaid.js.org/config/Tutorials.html](https://mermaid.js.org/config/Tutorials.html)
- mermaid在线编辑器[https://mermaid.live](https://mermaid.live/)
- 流程图的基本语法
	- 节点
		- ```mermaid
		  ---
		  title: Node
		  ---
		  flowchart LR
		      id
		  
		  ```
	- 有文本的节点
		- ```mermaid
		  ---
		  title: Node with text
		  ---
		  flowchart LR
		      id1[This is the text in the box]
		  ```
	- 流程图的方向
		- TB - top to bottom
		- TD - top-down/ same as top to bottom
		- BT - bottom to top
		- RL - right to left
		- LR - left to right
	- 节点的形状
		- 有圆边的矩形
			- ```mermaid
			  flowchart LR
			      id1(This is the text in the box)
			  ```
		- 体育场形节点
			- ```mermaid
			  flowchart LR
			      id1([This is the text in the box])
			  ```
		- ce
-