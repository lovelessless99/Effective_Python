# Effective_Python

> 為節錄 effective python 90 specific ways to write better python 的好味道 pythonic code 撰寫原則 

           
|已熟練運用 ?                      |做法          | 內容  | 備註 | 
|:--------------------------------:|:--------------:|:-----:|:-----:|
|<ul><li>- [x] </li></ul>         |4             | 優先使用 f-string 而非 str.format | |
|<ul><li>- [x] </li></ul>         |6             | 優先使用 多重指定的拆分而非索引 |  first, second, *others = one_list |
|<ul><li>- [x] </li></ul>         |7             | 優先使用 enumerate 而非 range ||
|<ul><li>- [x] </li></ul>         |8             | 使用 zip 平行處理迭代器  | 迭代器長度不同推薦 itertools.zip_longest |
|<ul><li>- [ ] </li></ul>         |10            | 以指定運算式避免重複 (python 3.8 walrus 符號) | 主要用在 if , while 判斷可以更優雅、簡潔，為 switch-case, do-while 替代方案 | 


