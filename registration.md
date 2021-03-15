# Register for ENAA XXXI

## Information on payment

The registration fee for this conference is 10€. 
## Registration form

To register for the virtual ENAA XXXI conference please use the form below. 

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<script>
    $(document).ready(function() {
        $("input[type='radio']").change(function() {
            if ($(this).val() == "other") {
                $("#otherAnswer").show();
            } else {
                $("#otherAnswer").hide();
            }
        });
    });
</script>

<form
  action="https://formspree.io/f/meqpyvlz"
  method="POST"
>
<label>
    Your email:
<br>
    <input type="email" name="_replyto" size="30" placeholder="example@institute">
  </label>
<br>
<label>
    Name:
<br>
    <input type="text" name="name" size="75" placeholder="Your Name">
  </label>
<br>
 <label>
    Institute:
<br>
    <input type="text" name="institute" size="75" placeholder="Your Institute">
  </label>
<br>
<br>
   <label>Waiver:</label>
<br>
      <input type="radio" id="none" name="waiver" value="none" required="required" checked="checked">
      <label for="none">None</label><br>
      <input type="radio" id="student" name="waiver" value="student">
      <label for="student">Student</label><br>
      <input type="radio" id="spa" name="waiver" value="spa">
      <label for="spa">SPA associate</label><br>
      <input type="radio" id="other" name="waiver" value="other">
      <label for="other">Other</label><br>
<input style="display:none;" type="text" size="75" name="otherAnswer" id="otherAnswer" />
<br>
  <button type="submit">Register</button>
</form>
