<header>
    <p style="font-size: 68pt"> my profile/<mark>about</mark></p>
    <h6><b> Hello, there! </b></h6>
</header>
<nav class="bg-dark" style="font-family:'Consolas'">
    <ul class="nav justify-content-center">
        <li class="nav-item">
          <a class="nav-link" href="#!"> my-profile/social </a>
        </li>
        <li class="nav-item">
          <a class="nav-link disabled" href="#!"> my-profile/about </a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#!"> myprofile/interests </a>
        </li>
      </ul>      
</nav>
<body style="background-color:beige">
    <!-- Content -->
    <br/>
    <div style="text-align: center">
        <img style= "border-radius: 50%" src="/static/profile-picture.jpg" alt="profile picture" width="240" height="240"/>
    <!-- These <p> tags are emptied purposely-->
    <p> </p>
    <h6 style="font-family: 'Consolas'; color: slateblue"> 🌱 <b> Khai Xiang Lim </b> </h6>
    <h6 style="font-family: 'Consolas'; color: slateblue"> 📍 <b> Penang, Malaysia </b> </h6>
    <h6 style="font-family: 'Consolas'; color: slateblue"> 👋 <b> Nice to meet you! </b> </h6>
    <hr/>
    <!-- Quote -->
    <div>
        <h3 style="color: slateblue; font-family: 'Consolas'"> " </h3>
        <h5> Declare variables, not wars; </h5> 
        <h5> Execute programs, not people! </h5> 
        <h3 style="color: slateblue; font-family: 'Consolas'"> " </h3>
    </div>
    <br/>
    </div>
    <h2> <b> My Projects > </b> </h2>
    <table>
        <tr>
            <td>
                <!-- first project slot -->
                <div class="card">
                    <img class="card-img-top" src="/static/project-1.jpg" alt="project-1 card image">
                    <div class="card-body">
                      <h4 class="card-title" style="font-family: 'Consolas'; background-color: slateblue; color: white"> > Play with Colors</h4>
                      <p class="card-text" style="color: slateblue; font-family: 'Consolas">
                        This web app that shows the color of what you typed.
                      </p>
                      <a href="https://github.com/khaixianglim/mini-project-4.git" class="btn btn-primary" style="background-color:slateblue; font-family: 'Courier'"> Github link </a>
                    </div>
                  </div>
            </td>
            <td>
                <div class="card">
                    <img class="card-img-top" src="/static/project-2.jpg" alt="project-2 card image">
                    <div class="card-body">
                      <h4 class="card-title" style="font-family: 'Consolas'; background-color: slateblue; color: white"> > My Profile </h4>
                      <p class="card-text" style="color: slateblue; font-family: 'Consolas">
                        This site introduces myself. Stay tuned!
                      </p>
                      <a href="https://github.com/khaixianglim/profile.git" class="btn btn-primary" style="background-color:slateblue; font-family: 'Courier'">Github link </a>
                    </div>
                  </div>
            </td>
        </tr>
    </table>
</body>
<footer>
    <p> <b>Credits</b> | Created on 23 October 2021 by Khai Xiang </p>
    <ul>
        <li> <b>Telebort</b> | <a href="https://www.telebort.com/" style="color: white"> Link </a> ⬅ <i> Learn coding here!</i> </li> 
        <li> <b> Svelte </b> | <a href="https://svelte.dev/" style="color: white"> Link </a> </li>
    </ul>
</footer>
<!-- CSS -->
<style>
    header{
        color: white;
        font-family:'Consolas', Courier, monospace;
        background-color: slateblue;
        text-align: center;
        padding: 80px;
    }
    h2{
        color: white;
        font-family: 'Consolas', Courier, monospace;
        background-color: slateblue;
        padding: 30px;
    }
    h5{
        color: slateblue;
        font-family: 'Consolas', Courier, monospace;
        font-weight: bold;
    }
    footer{
        font-family: 'Consolas', Courier, monospace;
        background-color: slateblue;
        padding: 50px;
        color: white;
        margin: auto;
    }
</style>