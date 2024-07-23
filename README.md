# Text parser to HTMML

`## Text ##`&ensp;&ensp;=&ensp;&ensp;`<h1>Text</h1>`\
`# Text #`&ensp;&ensp;=&ensp;&ensp;`<b>Text</b>`\
`[ Text ; Url ]`&ensp;&ensp;=&ensp;&ensp;`<a href="Url">Text</a>`\
`( Text ; Url )`&ensp;&ensp;=&ensp;&ensp;`<img src="Url" alt="Text"/>`\
`[ Url.mp4 ]` =      
`<div style="width: 100%" class="video">`\
&ensp;&ensp;&ensp;&ensp;`<video controls src=${videoURL}></video>`\
`</div>`