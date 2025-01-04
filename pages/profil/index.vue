<template>
  <div class="container-fluid foto text-center p-0">
    <img src="/assets/img/logo.png" alt="Logo" class="logo-img">
  </div>

  <nav class="navbar bg-body-tertiary">
    <div class="container-fluid">
      <span class="navbar-text">
        SAMBUTAN KEPALA SEKOLAH
      </span>
    </div>
  </nav>

  <div class="container-fluid foto text-center p-0 row align-items-center">
    <div class="d-flex align-items-center">
      <img src="/assets/img/kepala.png" alt="Kepala Sekolah" class="kepalaSekolah">
      <p class="p-2">Assalamu'alaikum warahmatullohi wabarokatuh...<br/><br/>
       kami berharap dengan adanya web site di SMK Negri 4 Tasikmalaya ini
       para pengunjung dapat mengenal lebih jauh tentang sekolah kami
       sehingga dapat mempererat tali silaurrahmi antara sekolah dengan
       masyarakat demi kemajuan kita bersama.
        <!-- Add the rest of the text here as needed -->
      </p>
    </div>
  </div>
</template>

<style scoped>
/* Ensure all images are responsive */
.foto { 
  max-width: 100%;
}

.logo-image {
  width: 100%;
  max-width: 100px; /* Adjust the max-width to control size */
  height: auto;
}

/* Navbar style */
.navbar {
  background-color: #6C9AAC;
  font-size: 30px; /* Fixed the incorrect font-size (60px0px) */
  padding: 20px 15px; /* Adjusted padding for better spacing */
}

.navbar-text {
  font-family: "Irish Grover", serif;
  font-weight: 400;
  color: #FBFDF6;
  font-size: 30px;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%); /* Centered the text */
}

/* Image of Kepala Sekolah */
.kepalaSekolah {
  width: 30%;
  object-fit: cover; /* Ensure image aspect ratio is preserved */
  border-radius: 50%; /* Optional: makes the image round */
}

/* Text styling */
p {
  font-size: 16px; /* Adjusted the text size for better readability */
  color: #333; /* Changed to a more readable color */
  text-align: justify;
  margin: 0 15px;
}
</style>
