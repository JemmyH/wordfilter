### 请求方式：POST/GET
#### 参数：content | string | 必须
#### 请求数据格式
```html
http://127.0.0.1:8006?content='需要过滤的文本'
```
#### 返回数据格式：json
#### 返回数据实例
```json
// 成功
{
  "result": "ok",
  "content": "**"
},
//失败
{
'result': 'fail',
}
```
