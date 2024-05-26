body{
    margin:0;
    padding:0;
    font-family: 'Poppins', sans-serif;
  }
  .holder{
    position:relative;
    width:100%;
    display:flex;
    height:100px;
    justify-content:center;
    align-items:center;
    flex-direction:column;
    overflow:hidden;
  }
  .holder:before{
    content:'';
    position:absolute;
    top:0;
    left:0;
    height:100%;
    width:100%;
    background: rgb(2,0,36);
    background: linear-gradient(90deg, rgba(2,0,36,1) 0%, rgba(77,86,88,1) 0%, rgba(75,66,52,1) 0%);
    transform:scaleX(1.5);
  }
  .heading{
    font-size:40px;
    font-weight:500;
    margin:5px;
    z-index:1;
    width:100%;
    color:#644947;
    text-align:center;
  }
  .tagline{
    z-index:1;
    font-size: 20px;
    font-weight: 200;
    width: 100%;
    color:#644947;
    text-align:center;
  }
