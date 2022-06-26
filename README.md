<style>
    /**
    * bodyタグ（文書本体）
    */
    body {
        background-color: #ffffff;
        color: #494949;
    }

    /**
    * codeタグ（コードテキスト）
    */
    code {
        font-family: "Meiryo", Menlo, Monaco, Consolas, "Droid Sans Mono", "Courier New", monospace, "Droid Sans Fallback";
    }

    /**
    * preタグ（整形済みテキスト）
    */
    pre {
        font-family: "Meiryo", Menlo, Monaco, Consolas, "Droid Sans Mono", "Courier New", monospace, "Droid Sans Fallback";
    }

    /**
    * blockquoteタグ（引用）
    */
    blockquote {
        border-color: #ea5219;
    }

    /**
    * h1タグ（見出し1）
    */
    h1 {
        color: #494949;
        font-weight: bold;
        border: solid 3px #ea5219;
        padding: 0.5em;
        border-radius: 0.5em;
    }

    /**
    * h2タグ（見出し2）
    */
    h2 {
        color: #494949;
        position: relative;
        font-weight: bold;
        margin: 0 0 1.5em;
        padding: 0.5em 0.5em 0.5em 2.1em;
        border-bottom: 2px solid #ea5219;
    }
    h2:before {
        content: "□";
        font-size: 180%;
        position: absolute;
        color: #ea5219;
        top: 0.15em;
        left: 0.1em;
        height: 12px;
        width: 12px;
    }
    h2:after {
        content: "□";
        font-size: 120%;
        position: absolute;
        color: #000000;
        top: 0.78em;
        left: 0;
        height: 12px;
        width: 12px;
    }

    /**
    * h3タグ（見出し3）
    */
    h3 {
        color: #494949;
        padding: .5em .75em;
        background-color: #f4f4f4;
        border-left: 6px solid #ea5219;
    }

    /**
    * h4タグ（見出し4）
    */
    h4 {
        color: #494949;
        padding: .5em .75em;
        background-color: #f4f4f4;
        border-radius: 6px;
    }

    /**
    * h5タグ（見出し5）
    */
    h5 {
        color: #494949;
        padding: .5em .75em;
        border-bottom-style: dotted;
        border-bottom-color: #ea5219;
        border-bottom-width:thin;
    }

    /**
    * tableタグ（表）
    */
    table thead th {
        background: #ea5219;
        font-weight: bold;
        vertical-align: top;
        color: #fff;
    }
    table th,
    table td {
        padding: 6px 13px;
        border: 1px solid #ddd;
    }
    table tr {
        background-color: #fff;
        border-top: 1px solid #ccc;
    }
    table tr:nth-child(2n) {
        background-color: #f8f8f8;
    }

    /**
    * hrタグ（水平線）
    */
    hr {
        background-color: #fff;
        border-color: #ea5219;
        border-top: 1px dashed #ea5219;
    }

    /**
    * ulタグ（リスト）
    */
    ul li{
        padding:0px;
        margin:0px;
    }
    ul li{
        list-style-type:none !important;
        list-style-image:none !important;
        margin: 5px 0px 5px 0px !important;
    }
    ul li{
        position:relative;
        padding-left:20px;
    }
    ul li:after{
        content:'';
        display:block; 
        position:absolute; 
        background:#ea5219;
        width:9px;
        height:9px; 
        top:5px; 
        left:5px; 
        transform:rotate(-45deg);
        -webkit-transform:rotate(-45deg);
        -o-transform:rotate(-45deg);
    }

    /**
    * olタグ（順序リスト）
    */
    ol {
        counter-reset:li;
        padding:0;
        list-style:none;
    }
    ol li {
        position:relative;
        margin:0 0 8px 4em;
        padding:2px 8px;
    }
    ol li:before {
        content:counter(li);
        counter-increment:li;
        position:absolute;
        top:-2px;
        left:-2em;
        width:2em;
        padding:3px 0;
        color:#fff;
        background:#ea5219;
        font-weight:bold;
        text-align:center;
        border-radius: 20px;
    }

    /**
    * aタグ（リンク）
    */
    a {
        color: #4078c0;
        text-decoration: none;
    }
    a:hover,
    a:active {
        text-decoration: underline;
    }
</style>

# hello world
