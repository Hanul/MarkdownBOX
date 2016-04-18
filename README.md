# MDBOX
Markdown BOX

## MD.MarkUp(md)
Markdown 문서를 `HTML`로 변경합니다.
```javascript
var html = MD.MarkUp('# MDBOX');
```

## MD.MarkUpDOM({ dom:, md: })
Markdown 문서를 `HTML`로 변경하여, `DOM`에 주입합니다.
```javascript
MD.MarkUpDOM({
	dom : div,
	md : '# MDBOX'
});
```

## MD.MarkdownSample()
Markdown 문법을 설명하는 샘플 화면을 띄웁니다.
```javascript
MD.MarkdownSample().appendTo(BODY);
```

## 라이센스
[MIT](LICENSE)

## 작성자
[Young Jae Sim](https://github.com/Hanul)