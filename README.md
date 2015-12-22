# Json Resume - Material theme 

This is the material theme for [JSON Resume](http://jsonresume.org/).

Added `projects` tag，responsive design.

![](http://ww2.sinaimg.cn/large/6d0af205jw1ez8gjtzslsj20tu0hb0vn.jpg)

## Getting started

### Install Node.js

If you don't know how to install `node.js` and `npm`, see these:

- [node.js](http://howtonode.org/how-to-install-nodejs)
- [npm](http://howtonode.org/introduction-to-npm)

### Download theme

Lets go ahead and download a [copy of the repository](https://github.com/hectorguo/jsonresume-theme-material/archive/master.zip).

### Install npm packages

We need to install the dependencies. `cd` into the theme folder we just downloaded and run:

```bash
npm install
```

This will read the local `package.json` and install the packages listed under `dependencies`.

### Serve theme

While inside the theme folder, simply run:

```
npm start
```

You should now see this message:

```
Preview: http://localhost:4000
Press ctrl-c to stop
```

Congratulations, you've made it!

__The theme development can now begin.__

### Fill your resume

`resume.json` is your resume data, modify it to yourself's.

In this template, only `summary` can be inserted into html `tag`, such as 

``` json
{
  "name": "Personal",
  "summary": "<a href=\"http://hectorguo.com/en/projects/\">Projects Page</a>"
}
```

## Custom

`resume.hbs` is the template file, its syntax is based on [handlebars](http://handlebarsjs.com/).

`style.css` defines your styles. Technically, this is completely optional, as you could just write all of your styles in the `<style>` tags of your `resume.template`. As the `index.js`, the contents of the `style.css` are put into the `<style>` tags of your compiled theme later, yet again, this is something can change.

## License

Available under [the MIT license](http://mths.be/mit).

## 中文指南

1. 首先，确保已经安装 [node.js](http://howtonode.org/how-to-install-nodejs) 和 [npm](http://howtonode.org/introduction-to-npm)。

2. 下载该主题包：

  [点此下载](https://github.com/hectorguo/jsonresume-theme-material/archive/master.zip)

  下载依赖包：

  在下载解压后的目录，输入：

  ```bash
  npm install
  ```

3. 修改简历

  在`resume.json`中修改简历数据，或者直接 [在线编辑](http://registry.jsonresume.org/) 并生成你的json版简历。
  新增`项目经历`类目，详情可在样例中查看。

4. 在当前目录运行：

  ```
  npm start
  ```

  此时目录中会生成一个 `index.html`文件，即简历。



