<p align="center">
  <img id="welcome-banner" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=640&section=header&text=Welcome%20to%20My%20GitHub!&fontSize=60&fontColor=white&animation=fadeIn" />
</p>

<script>
  const themes = ["gradient", "blue", "purple", "pink", "red"];
  let index = 0;

  function changeTheme() {
    index = (index + 1) % themes.length;
    document.getElementById("welcome-banner").src = `https://capsule-render.vercel.app/api?type=waving&color=${themes[index]}&height=640&section=header&text=Welcome%20to%20My%20GitHub!&fontSize=60&fontColor=white&animation=fadeIn`;
  }

  setInterval(changeTheme, 5000); // Change theme every 5 seconds
</script>
