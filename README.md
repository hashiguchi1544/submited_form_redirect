# フォーム送信後に任意のページに飛ばす方法。

ここでは、form.htmlでフォームを送信したら、submited_form.htmlにリダイレクトしてます。
google formで送信後に任意のページに飛ばしたいときに重宝します。

フォームが送信されたら、JavaScriptの関数が呼び出され、強制リダイレクトをします。

## 補足

formの属性は、**target**, **onsubmit**を使用します。

iframeのnameの属性値は、formのtargetの属性値と同じにします。

iframeのstyle="display:none"をしなければ送信後のgoogle formの送信後ページが一瞬写ってしまいます。

iframeのonloadの属性値を呼び出したいJavascriptの関数にします。
