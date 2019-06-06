# CreditEntryScreen

![CreditEntryScreen](https://iheno.github.io/CreditEntryScreen/img/screen.png "CreditEntryScreen")


# CreditEntryScreenr

## css

### set.css
```
body {
  background-color: rgb(252, 251, 252);
  font-family: "PingFang SC", "LiHei Pro", 新細明體, sans-serif !important;
}
body {
  line-height: 1;
}
html, body, div, span, applet, object, iframe, h1, h2, h3, h4, h5, h6, p, blockquote, pre, a, abbr, acronym, address, big, cite, code, del, dfn, em, img, ins, kbd, q, s, samp, small, strike, strong, sub, sup, tt, var, b, u, i, center, dl, dt, dd, ol, ul, li, fieldset, form, label, legend, table, caption, tbody, tfoot, thead, tr, th, td, article, aside, canvas, details, embed, figure, figcaption, footer, header, hgroup, main, menu, nav, output, ruby, section, summary, time, mark, audio, video {
  vertical-align: baseline;
  margin: 0px;
  padding: 0px;
  border-width: 0px;
  border-style: initial;
  border-color: initial;
  border-image: initial;
  font: inherit;
}

hr {
  display: block;
  unicode-bidi: isolate;
  margin-block-start: 0.5em;
  margin-block-end: 0.5em;
  margin-inline-start: auto;
  margin-inline-end: auto;
  overflow: hidden;
  border-style: inset;
  border-width: 1px;
}

button, button:focus {
  outline: none;
  border: none;
  cursor: pointer;
}

```

### credit.css

```

.creditWarp {
  display: flex;
  flex-direction: column;
  -webkit-box-align: center;
  align-items: center;
}
@media (min-width: 481px) {
.creditWarp {
  min-height: 716px;
  }
}
.credit__box {
  display: flex;
  flex-direction: column;
  box-sizing: border-box;
  width: 100%;
  background-color: rgb(255, 255, 255);
  box-shadow: rgba(221, 221, 221, 0.5) 0px 0px 1px 0px;
  padding: 50px 20px;
}

@media (min-width: 481px) {
.credit__box {
  max-width: 420px;
  margin: 60px 0;
  padding: 50px;
  border-width: 1px;
  border-style: solid;
  border-color: rgb(227, 227, 227);
  border-image: initial;
  border-radius: 2px;
  }
}

.credit__title h3{
  font-size: 17px;
  color: rgb(0, 0, 0);
  font-weight: 600;
}
.credit__title p {
  font-size: 10px;
  padding: 15px 0 0 0;
  color: #666d75;
}
.credit__title ul {
  padding: 10px 0;
}
.credit__title ul li {
  float: left;
  list-style: none;
  margin-right: 3px;
}
.credit__title ul li img {
  width: 38px;
  height: 26px;
  object-fit: contain;
  border: 1px solid rgb(238, 238, 238);
  border-radius: 4px;
  padding: 0 5px;
}

.boxLinner {
  height: 1px;
  background-color: rgb(227, 227, 227);
  border-width: 0px;
  border-style: initial;
  border-color: initial;
  border-image: initial;
  padding: 0px;
  margin: 30px 0px 14px;
}

.credit__form {
  display: flex;
  flex-direction: column;
  padding-top: 16px;
}
.credit__select, .credit__cvv {
  padding-top: 16px;
  padding-top: 16px;
}

.credit__form__label {
  height: 18px;
  font-size: 13px;
  color: rgb(0, 0, 0);
  margin-bottom: 8px;
}
.credit__form__input {
  height: 38px;
  font-size: 16px;
  color: rgb(0, 0, 0);
  padding-left: 10px;
  padding-right: 10px;
  box-shadow: rgba(221, 221, 221, 0.5) 0px 0px 2px 0px;
  -webkit-appearance: none;
  border-radius: 2px;
  border-width: 1px;
  border-style: solid;
  border-color: rgb(227, 227, 227);
  border-image: initial;
}

.credit__form__input:focus {
  outline: none;
  border-width: 1px;
  border-style: solid;
  border-color: rgba(233, 30, 99, 0.3);
  border-image: initial;
}

.credit__form__input::placeholder {
  color: rgb(202, 202, 202);
  font-size: 13px;
}

.credit__select {
  float: left;
}
.credit__cvv {
  float: right;
}
.credit__info {
  margin-top: 8px;
}
.credit__info li {
  display: block;
  float: left;
  list-style: none;
  margin-right: 5px;
}
.credit__info li:last-child {
  margin-right: 0;
}
.credit__form__select {
  height: 42px;
  display: block;
  font-size: 16px;
  color: rgb(0, 0, 0);
  box-shadow: rgba(221, 221, 221, 0.5) 0px 0px 2px 0px;
  -webkit-appearance: none;
  border-radius: 2px;
  border-width: 1px;
  border-style: solid;
  border-color: rgb(227, 227, 227);
  background-color: #ffffff;
  background: url(../img/select-arrow.png) no-repeat;
  background-size: 10px 16px;
  padding: 0 12px 0 12px;
}
.credit__form__select:focus{
  outline: none;
  border-width: 1px;
  border-style: solid;
  border-color: rgba(233, 30, 99, 0.3);
  border-image: initial;
}
.dateSelectMon {
  width: 60px;
  background-position: 42px center;
}
.dateSelectYear {
  width: 80px;
  background-position: 62px center;
}
.dateCvv {
  width: 108px;
  overflow: hidden;
  background: url(../img/cvv.svg) no-repeat;
  background-size: 40px 25px;
  background-position: 82px center;
}
.credit__btn {
  display: flex;
  flex-direction: column;
  -webkit-box-align: center;
  align-items: center;
  padding-top: 50px;
}

.credit__btn .creditBtn {
  width: 100%;
  max-width: 320px;
  height: 48px;
  box-shadow: rgba(221, 221, 221, 0.5) 0px 0px 2px 0px;
  background-color: rgb(233, 30, 99);
  border-radius: 2px;
  border: 
}



.credit__btn .creditBtn span {
  height: 24px;
  font-size: 17px;
  font-weight: 600;
  color: rgb(255, 255, 255);
}

```

## html 

```
<!DOCTYPE html>
<html lang="">

<head>
	<meta charset="utf-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<title></title>
	<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
	<meta name="description" content="" />
	<meta name="keywords" content="" />
	<meta name="author" content="" />
	<link rel="shortcut icon" href="">
	<meta property="og:title" content="" />
	<meta property="og:image" content="" />
	<meta property="og:url" content="" />
	<meta property="og:site_name" content="" />
	<meta property="og:description" content="" />

	<link rel="stylesheet" href="css/set.css">
	<link rel="stylesheet" href="css/credit.css">

</head>

<body>
<div class="creditWarp">
<div class="credit__box">
<div class="credit__title">
<h3>My Credit Card</h3>
<p>Available credit cards</p>
<ul>
	<li><img src="img/visa.svg" alt="visa" /></li>
	<li><img src="img/mastercard.svg" alt="mastercard" /></li>
</ul>
</div>
<hr class="boxLinner">
<form>
<div class="credit__form">
	<label class="credit__form__label">Card Number</label>
	<input class="credit__form__input" placeholder="**** **** **** ****" type="tel" maxlength="19" autocomplete="cc-number">
</div>
<div class="credit__form">
	<label class="credit__form__label">Name</label>
	<input class="credit__form__input" placeholder="Name（english）" autocomplete="cc-name">
</div>
<div class="credit__select">
<label class="credit__form__label">Validity Period</label>
<ul class="credit__info">
<li>
<select class="credit__form__select dateSelectMon" title="Month">
<option value="0">01</option>
<option value="1">02</option>
<option value="2">03</option>
<option value="3">04</option>
<option value="4">05</option>
<option value="5">06</option>
<option value="6">07</option>
<option value="7">08</option>
<option value="8">09</option>
<option value="9">10</option>
<option value="10">11</option>
<option value="11">12</option>
</select>
</li>
<li>
<select class="credit__form__select dateSelectYear" title="Year">
<option value="0">2019</option>
<option value="1">2020</option>
<option value="2">2021</option>
<option value="3">2022</option>
<option value="4">2023</option>
<option value="5">2024</option>
<option value="6">2025</option>
<option value="7">2026</option>
<option value="8">2027</option>
<option value="9">2028</option>
<option value="10">2029</option>
<option value="11">2030</option>
</select>
</li>
</ul>
</div>
<div class="credit__cvv">
<label class="credit__form__label">CVV / CVC</label>
<div class="credit__info">
<input class="credit__form__input dateCvv" placeholder="CVV" type="number" maxlength="4">
</div>
</div>
</form>

<div class="credit__btn">
<button type="submit" class="creditBtn"><span>Registration</span></button>
</div>
</div>

</div>

</body>

</html>



```



