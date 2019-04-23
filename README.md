# tableDrag
表格表头的固定，表内容的滚动。表格可拖拽表头修改对应表格内容一列的宽度。

思路：主要依靠两个table来实现。<br/>
1,fileDirTable是表头，fileDirTableBody 是表格内容。<br/>
2,因为表格的列宽度是由数据撑开的，所以需要一个初始值来统一大小<br/>
'<colgroup class="fileCol"><col width="170px"></col><col width="170px"></col><col width="170px"></col><col width="170px"></col><col width="170px"></col></colgroup>'
