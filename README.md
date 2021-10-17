# checkout-form
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Check Out</title>
    <link rel="stylesheet" href="index.css">
    <script src="https://kit.fontawesome.com/5c7edfd842.js" crossorigin="anonymous"></script>
</head>
<body>
    <h1 class="title">Checkout</h1>
    <div class="contact-information">
        <h2>Contact Information</h2>
        <form action="#">
            <label for="email">Email</label>
            <div class="text-field">
                <i class="fas fa-envelope"></i>
                <input type="text" class="input-text" id="email">
                
            </div>

            <label for="phone">Phone</label>
            <div class="text-field">
                <i class="fas fa-phone-alt"></i>
                <input type="text" class="input-text" id="phone">
                
            </div><br>
            
            <h2>Shipping address</h2>
            <label for="name">Full Name</label>
            <div class="text-field">
                <i class="fas fa-user"></i>
                <input type="text" class="input-text" id="name">
                
            </div>
            

            <label for="address">Address</label>
            <div class="text-field">
                <i class="fas fa-home"></i>
                <input type="text" class="input-text" id="address">
                
            </div>
            

            <label for="city">City</label>
            <div class="text-field">
                <i class="fas fa-city"></i>
                <input type="text" class="input-text" id="city">
                
            </div>
            
            <div class="conpost">
                <div class="a">
                <label for="country">Country</label>
                <div class=>
                    <i class="fas fa-globe-europe"></i>
                    <select name="country" id="country" class="country"required>
                        
                 <option value="">Turkey</option>
                    <option value="">Germany</option>
                    <option value="">USA</option>
                    <option value="">Canada</option>
                    <option value="">UK</option>
                    </select>
                </div>
                <div>
                    <label for="postcode">Postcode</label>
                    <div class="text-field-postcode">
                    <i class="fas fa-mail-bulk"></i>
                    <input type="text" class="postcode" id="postcode">
                </div>
                </div>
                    <!-- <label for="postcode">Postcode</label>
                    <div class="text-field-postcode">
                    <i class="fas fa-mail-bulk"></i>
                    <input type="text" class="postcode" id="postcode"> -->
                    
                </div>
            </div>

            <div class="checkbox">
                <input type="checkbox" name="chkbox" id="chkbox">
                <label for="chkbox" class="chkbox">See this information time</label>
                
            </div>

            <input type="button" class="button" value="Continue">


          
        </form>
    </div>


</body>
</html>


*{
    margin: 0;
    padding:0;
    box-sizing: border-box;
    font-family: "Mon" , sans-serif;
    color: rgb(77, 76, 76);
    /* line-height: 30px; */
}
@font-face{
    font-family: Mon;
    src: url('FONTS/Montserrat-Regular.ttf');
}
.contact-information{
    position: relative; 
    width: 50%;
    height: auto;
    border: 1px solid red;
    margin: 25px;
}
.title{
    font-family: Mon, Arial, Helvetica, sans-serif;
    text-align: center;
    margin: 15px 0;
}

.text-field, .country{
    position: relative;
    height: auto;
    width: auto;
    border: 1px solid #828282;
    padding: 4px 0px 4px 0px;
    border-radius: 5px 5px 5px 5px;
}
.input-text{
    width: 400px;
    border: none;

}
.postcode{
     
    display: inline-block;
    height: auto;
    width: 25px;
    border: 1px solid #828282;
    padding: 4px 0px 4px 0px;
    border: none;
}
.text-field-postcode{
    display: inline-block;
  
    width: 200px;
    border: 1px solid #828282;
    padding: 4px 0px 4px 0px;
    border-radius: 5px 5px 5px 5px;
}
.country{
    display: inline-block;
}
.conpost{
    margin-top: 10px;
    /* position: relative; */
    
}


