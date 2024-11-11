<template>
    <div>
        <NavMasthead />

        <div class="content-wrap content-wrap--bg-matt content-wrap--flex">
            <div class="content-wrap__box content-wrap__box--narrow content-wrap--margin-tb">
                <h1>Contact me</h1>

                <p>You can find me on linked in <a href="http://linkedin.com/in/matthewoshinowo/" target="_blank">here</a></p>

                <form action="https://api.staticforms.xyz/submit" method="post" class="form">
                    <p>Or fill in this form to email me directly:</p>                  

                    <input type="hidden" name="accessKey" value="ccfa0f3a-0514-4f55-82b8-65a283206098">

                    <label for="name">Your name</label>
                    <input type="text" name="name">

                    <label for="email">Your email address</label>
                    <input type="email" name="email">

                    <label for="subject">Subject</label>
                    <input type="text" name="subject">

                    <label for="message">Message</label>
                    <textarea name="message"></textarea>
                    
                    <input type="hidden" name="redirectTo" value="https://kimoshinowo.github.io/matt-website/contact">
                    <input type="submit" value="Email me" />
                </form>
            </div>
        </div>
    </div>
</template>
  
<script>
export default {
    // page properties go here
}
</script>