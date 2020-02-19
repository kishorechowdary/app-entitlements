	title: What is WordPress?
slug: what-is-wordpress
acf1: for example, text
acf2: for example, an URL
Metainfo above and won't show in the final page.
Support Chinese is very important:
## headings below
# 一级标题 heading 1
## 二级标题 heading 2
### 三级标题 heading 3
#### 四级标题 heading 4
##### 五级标题 heading 5
###### 六级标题 heading 6
## bold/italic/delete below
**Bold用两个星号标记起来，表示加粗**， *Italic一个星号，表示斜体* ，~~delete line这样子表示删除~~，这些就是最基本的语法了。
## code below
分别对应HTML中的`this is inline code`，以此类推。
this is block code
```
def isLeapYear(n):
    # write your code here
    if n % 4 != 0 or n % 100 == 0 and n % 400 != 0:
        return False
    elif n % 4 == 0 or n % 400 == 0:
        return True
print(isLeapYear(2004))
```
or I can setting which code sould it display:
```js
<script>
    function copy(text) {
      var textarea = document.createElement("textarea");
      textarea.value = text;
      document.body.appendChild(textarea);
      textarea.select();
      document.execCommand("copy");
      document.body.removeChild(textarea);
    }
</script>
```
forms below:
```table
H1 | aha testing
OK | good
yes | with
```
## links below
**插入链接:**
这是一个 [link anchor name](http://url.com/)
**快速链接:**
只需要在网址头尾用尖括号包裹即可，比如<http://url.com>
**邮箱链接:**
这是一个 <myname@example.com> 邮箱的链接。
## lists below
**无序列表:**
- Red
- Green
- Blue
**有序列表则使用数字接着一个英文句点：**
1.  Bird
2.  McHale
3.  Parish
**也可以混合在一起使用:**
- Bird
    - blue bird
- McHale
    1. a man
    2. HoustonRockets
- Parish
task list(important!):
- [] this is task list
- [x] this is task list
- [] this is task list
- [] this is task list
## 分割线
**`-`加上空格组成，三个以上:**
devider line
- - - - - -
## single line quote below
>  Markdown是非常棒以及流行的写作语法，平文本，「易读易写」，一般只需几分钟就能学会Markdown的基本用法。
## multi-lines quote
> 你
> 一会看我
> 一会看云

>  我觉得
>  你看我时很远
>  你看云时很近

## images
> 插入图片的语法跟插链接很像，在MarkEditor中，一般可以通过拖拽的方式进行插图，不一定会看到这个语法，而可能直接看到图片本身。
![](./_image/2020-02-17-16-19-05.png)
的形式中，如果图片的 url 不是 Web 地址，而是本地的指向，则后面跟上`?r=90&w=100&h=100`，可以设定图片的尺寸。其中 r 表示缩放90%,  w 表示最大宽度 (像素)，h 表示最大高度。r、w、h 并不需要全部进行声明，按需则可。
如果是图片直接在编辑区域内可见(非 Markdown 语法显示)，双击图片，可以直接进行调整。