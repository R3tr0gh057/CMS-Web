<script>
    //javascript for the login page
    import Button from '$lib/components/Button.svelte';
</script>

<main>
    <!--html for the login page-->
    <!--main logo-->
    <div class="main_img">
        <img src="https://upload.wikimedia.org/wikipedia/en/thumb/2/29/KJC_logo.jpg/512px-KJC_logo.jpg" alt="kjc logo">
    </div>

    <div class="title_sub">
        <h3>Welcome to KJC</h3>
        <h4>Component Management System</h4>
    </div>

    <div class="login_box">
        <div class="user_field">
            <p>User Name / Email</p>
            <!--component call for username field-->
        </div>
        <div class="passwd_field">
            <p>Password</p>
            <!--component call for password field-->
        </div>
        <div class="action_btns">
            <!--component call for btn1-->
            <Button variant = "success">Login</Button>
            <!--component call for btn2-->
            <Button variant = "danger">About</Button>
        </div>
    </div>

    <footer>
        <p>Version 1.0.0</p>
    </footer>


</main>

<style>
    main{
        display: flex;
        align-items: center;
        flex-direction: column;
        width: 100%;
        background-image: none;
    }

    .main_img img{
        width: 200px;    
    }


    .login_box {
        display: flex;
        flex-direction: column;
        align-items: center;

        width: 284px;
        padding: 10px 10px 20px 10px;
        border: 2px solid #BFBFBF;
        background-color: white;
        box-shadow: 1px 1px 6px #aaaaaa
    }

</style>