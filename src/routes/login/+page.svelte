<svelte:head>
	<title>Login</title>
	<meta name="description" content="Login Page" />
</svelte:head>

<div class="text-column">
	<h1>OM Squash</h1>

  <input type="text" placeholder="Username">  
  <input type="password" placeholder="Password">
  <button>Login</button>

</div>

<style>
  div {
    width: 50%;
    background: #001a33;
    display: flex;
    flex-direction: column;
    align-items: center;
    justtify-content: space-between;
  }

  h1 {
    color: white;
  }

	input {
    height: 30px;
    margin-top: 10px;
    margin-bottom: 10px;
		width: 80%;
    border: none; 
    border-radius: 6px;
    box-shadow: 5px 5px #9de0ad;
    text-align: center;
	}

  button {
    height: 30px;
    background: #9de0ad;
    margin-top: 10px;
    margin-bottom: 10px;
    width: 80%;
    border: none;
    border-radius: 6px;
    box-shadow: 5px 5px #547980;
  }

button:hover {
/*	text-decoration: underline; */
  color: white;
    box-shadow: 9px 9px #547980;
}

  ::placeholder {
      text-align: center;
    }
</style>
