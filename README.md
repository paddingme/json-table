json-table
==========


数据格式：
[{id:'XX',classifyName:'XXXX',aa:'xxx'},{...},{...},...]，对象组成的数组。

表格：
<table id="  "  class="   "  > 
<thead>
<tr>
<th  >classifyName</th>
<th  >XX </th>
<th  >AAA </th>
<th >DDDD</th>
<th >WWW </th>
<th >QQQQ </th>
</tr>
</thead>
<tbody>
</tbody>
</table>

需求：
向表格传入数据，表格自动生成。如调用函数 initTable(tableId, columnNumber)//tableId:表格的ID，columnNumber：需要合并的列号。
合并classifyName列中相同内容的单元格。所给数据提前已经按classifyName排序。
