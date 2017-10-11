# test2
<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="utf-8">
<title>form</title>


<style type="text/css">
body{
  background-color:rgb(176,224,230)
}

form input:focus:invalid {
  border : tomato 2px solid;
}
form input:valid:not(:last-child) {
  border : seagreen 2px solid;
}

</style>
</head>


<body>

  <script type="text/javascript">

 </script>

<form>
  <div>
    　　名前<input type="text" placeholder="氏名" required/>
  </div>

  <div>
    郵便番号<input type="number" pattern="\d{3}-\d{4}" placeholder="123-4567" required/>
  </div>

  <div>
    　　住所<input type="text" placeholder="千葉県千葉市～" required/>
  </div>

  <div>
    電話番号<input type="tel" placeholder="09012345678" required/>
  </div>
</form>
</body>
