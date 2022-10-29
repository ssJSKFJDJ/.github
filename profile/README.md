# ssJSKFJDJ

[![License](https://img.shields.io/github/license/ssJSKFJDJ/.github.svg)](http://www.gnu.org/licenses)<br>
[![Netlify Status](https://api.netlify.com/api/v1/badges/9452c174-42c2-44b3-b3e5-90e79fda77c4/deploy-status)](https://ssjskfjdj.netlify.app/)<br>
[![](https://img.shields.io/badge/☃️ssJSKFJDJ♬-971050440-blue)](https://jq.qq.com/?_wv=1027&k=y81MmDpz)<br>
[![](https://img.shields.io/badge/team-Dice!-black)](https://github.com/orgs/ssJSKFJDJ/teams/dice/repositories)
[![](https://img.shields.io/badge/team-OlivaOS-black)](https://github.com/orgs/ssJSKFJDJ/teams/olivaos/repositories)<br>
[![](https://img.shields.io/github/directory-file-count/ssJSKFJDJ/plugin?label=plugin)](https://github.com/ssJSKFJDJ/plugin)
[![](https://img.shields.io/badge/Dice%20mod-3-orange)](https://github.com/search?q=topic%3Adice-mod+org%3AssJSKFJDJ+fork%3Atrue&type=repositories)
[![](https://img.shields.io/github/directory-file-count/ssJSKFJDJ/PublicDeck?label=PublicDeck)](https://github.com/ssJSKFJDJ/PublicDeck)
[![](https://img.shields.io/badge/Lua%20Module-1-orange)](https://github.com/search?q=topic%3Alua-module+fork%3Atrue+org%3AssJSKFJDJ&type=Repositories)<br>

> for script or mod.

<img src="https://ghchart.rshah.org/cypress0522" />

# Contribute

## plugin

> 如果你是Dice!脚本作者，那么你可以[fork plugin](https://github.com/ssJSKFJDJ/plugin)仓库，然后按格式提交PR。

## PublicDeck

> 如果你是牌堆作者，那么你可以[fork PublicDeck](https://github.com/ssJSKFJDJ/PublicDeck)仓库，然后按格式提交PR。

## Module

功能模块。是“主营业务”。
功能模块的收集没有任何像plugin或PublickDeck那样的专门的库，这里只选择功能模块作者在main-pages的master分支的[Module](https://github.com/ssJSKFJDJ/main-pages/tree/master/docs/Module)文件夹下提交功能模块远程下载json的方式来收录Module。在收到PR以及审核通过后，审核人员会将你的功能模块库fork到ssJSKFJDJ。

其一般步骤如下：
1. [fork](https://github.com/ssJSKFJDJ/main-pages/fork) main-pages库。一切都是从这里开始的。
2. 提交你的包含"pkg"字段的功能模块json：
   比如[listen2me](https://github.com/ssJSKFJDJ/listen2me)库提供的json是这样的：
   ```json
   {
     "mod":"listen2me",
     "author":"简律纯",
     "ver":"1.1.8",
     "dice_build":612,
     "brief":"使用mml作曲",
     "pkg":"https://github.com/cypress0522/listen2me/releases/download/v1.1.8/listen2me_v1.1.8.zip",
     "comment":"",
     "helpdoc":{
         "listen2me":"【listen2me[Windows]】\n使用mml语言进行作曲\nhttps://github.com/cypress0522/listen2me"
     }
   }
   ```
   你可以直接[访问](https://github.com/ssJSKFJDJ/main-pages/blob/master/docs/Module/listen2me)来查看该json所在位置。
   这里我们只需要填写"pkg"字段即可，"repo"字段如有请删除。
   > tips:pkg填写的是把功能模块打包好后发布的地址，必须为直链，不一定要在github上!
3. 给你的功能模块库添加`lua`和`dice-mod`标签。
4. 按照格式提交PR。
5. 如有需要一并提交md格式的技术文档。

***

```
  MIT License

Copyright (c) 2022 ssJSKFJDJ

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
