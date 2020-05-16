# 勤怠システムを開発しよう！

これはセレブエンジニアサロンの教材で作られたサンプルアプリケーションです。

## 開発環境

* AWS Cloud9
* Ruby
* Rails
* Git(HTTPSからSSH通信へ変更)
* 
!--<form id="form1" action= search_users_path, method="get">-->
<!--<input id="sbox1" id="s" name="s" type="text" placeholder="キーワードを入力" />-->
<!--<input id="sbtn1" type="submit" value="検索" /></form>-->


<!--★検索キーワード入力欄とボタンが横並びになった検索ボックスを作る-->
<!--右寄せ https://uguisu.skr.jp/html/center.html-->
<!--<div align="right"><form action="search", method="get">-->
  <!--name=qで検索文字 placeholder="キーワード"-->
	<!--<input  type="search" name="q" value="" ><input type="submit" name="btn_search" value="検索">-->
<!--</form></div>-->

<!--●HTML一体型<form id="form01" action="#">-->
    <!--<input id="input01" type="text"><!---->
    <!--/input間で改行したい場合はコメントアウト必須/-->
    <!----<input id="submit01" type="submit" value="検索">-->
<!--</form>-->
<!---->＿
 <!--検索拡張機能 -->
 <!--<div align="right">-->
      <!--<p>ユーザー名検索</p>-->
      <!--%= form_tag users_path, :method => 'get' do %>-->
          <!--%= text_field_tag :search, params[:search] %>-->
          <!--%= submit_tag "検索", :name => nil %>-->
        </div>
      <!--% end %>-->
      
  <!--%= form_with(url: search_users_path, local: true, method: :get, class: "search-form") do |form| %>-->
  <!--%= form.text_field :keyword, placeholder: "投稿を検索する", class: "search-input" %>-->
  <!--%= form.submit "検索", class: "search-btn" %>-->
<!--% end %>-->

<!--初めに実装%= form_with url: search_users_path, method: :get, local: true do |f| %>-->
  <!--%= f.text_field :name %>-->
  <!--%= f.submit :search %>-->
<!--% end %>-->
