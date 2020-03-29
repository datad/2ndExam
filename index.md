<?php     
$to_email = 'dianmante@gmail.com';
$subject = 'Testing PHP Mail';
$message = 'This mail is sent using the PHP mail function';
$headers = 'From: dianmante@gmail.com';
mail($to_email,$subject,$message,$headers);
?>

## CS261 - 2nd Midterm

# Question

Answer

<p>
This is an email link:
<a href="mailto:dianmante@gmail.com?Subject=Hello%20again" target="_top">Send Mail</a>
</p>

<p>
<b>Note:</b> Spaces between words should be replaced by %20 to ensure that the browser will display the text properly.
</p>
