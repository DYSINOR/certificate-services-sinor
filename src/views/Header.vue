<template>
    <header class="header">
      <div class="request-text">ដាក់ពាក្យស្នើសុំ /</div>
      <div class="nav-icons">
        <div class="icon-item">
            <img src="../assets/img/user-icon.png"/>
          <i class="fas fa-info-circle"></i>
          <span>ព័ត៌មាន</span>
        </div>
        <div class="icon-item">
          <img src="../assets/img/logout-icon.png" alt="Logout Icon">
          <i class="fas fa-file-alt"></i>
          <span>ចាកចេញ</span>
        </div>
      </div>
    </header>
  </template>
  
  <script>
  export default {
    name: 'Header'
  }
  </script>
  
  <style scoped>
  @import url('https://fonts.googleapis.com/css2?family=Kantumruy&display=swap');
  
  .header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 16px 82px;
    width: 100%;
    height: 70px;
    background: #FFFFFF;
    box-shadow: 0px 8px 16px rgba(0, 0, 0, 0.15);
  }
  
  .request-text {
    font-family: 'Kantumruy', sans-serif;
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 24px;
    color: #3074FD;
  }
  
  .nav-icons {
    display: flex;
    gap: 16px;
  }
  
  .icon-item {
    display: flex;
    align-items: center;
    gap: 8px;
    color: #3074FD;
    font-family: 'Kantumruy', sans-serif;
    font-size: 16px;
  }
  
  .icon-item i {
    font-size: 18px;
  }
  </style>
  