S.No.- 01
date- 26/07/2021
file name- payment form
problems- i had problem in writing input type and etc.
solution- i watched youtube video and wrote this here
<body>
    <form action="">
        <h1>payment form</h1>
        <p>Required Fileds are followed by *</p>
        <h2>contact information</h2>
        <p>Name: * <input type="text" name="name" required></p>
        <fieldset>
            <legend>Gender * </legend>
            <p>
            Male <input type="radio" name="gender" id="Male" required>
            Female <input type="radio" name="gender" id="female" required>
            </p>
       </fieldset>
       <p>Address: <textarea name="address" id="address" cols="100" rows="8"></textarea></p>
       <p>Email: * <input type="email" name="email" id="email" required></p>
       <p>Pincode: * <input type="number" name="pincode" id="pincode" required></p>
       <hr>
       <h2>Payment information</h2>
       <p>Card type: *
           <select name="card_type" id="card_type"required>
           <option value="">--select a card type--</option>
           <option value="visa">visa</option>
           <option value="rupay">rupay</option>
           <option value="mastercard">mastercard</option>
        </select>
       </p>
       <p>
           Card Number: * <input type="number" name="card number" id="card number" required>
       </p>
       <p>
           Expiration date: * <input type="date" name="exp_date" id="exp_date" required>
       </p>
       <p>CVV: * <input type="password" name="cvv" id="cvv" required></p>
       <input type="submit" value="Pay Now">
    </form>
</body>
