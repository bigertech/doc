#笔戈博客新增 helpers

## next_post
异步获取下一篇博客，

* `postId`   当前文章的ID
* `limit`   需要输出的文章的数量 默认1  


**Example** : 获取 id = 49 的文章的，下两篇文章  

```
		{{next_post postId="49" limit=2}}
```
**Result:**

```
{posts:[Post,Post2....]}
```
## pre_post
异步获取上一篇博客，

* `postId`   当前文章的ID
* `limit`   需要输出的文章的数量 默认1
example: 获取 id = 49 的文章的，下两篇文章  

```
		{{pre_post postId="49" limit=2}}
```

