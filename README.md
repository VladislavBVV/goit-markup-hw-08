.background {
  background: $footer-beckground-color;
  text-align: center;
  // padding-top: 200px;
  // padding-bottom: 200px;
  //
  margin-right: auto;
  margin-left: auto;
  max-width: 1600px;
  background-repeat: no-repeat;
  @media screen and (min-width: 320px) {
    padding-top: 118px;
    padding-bottom: 118px;

    background-image: linear-gradient(
        rgba(47, 48, 58, 0.4),
        rgba(47, 48, 58, 0.4)
      ),
      url(../image/hero-m-x1-min.jpg);
    @media (min-device-pixel-ratio: 2),
      (min-resolution: 192dpi),
      (min-resolution: 2dppx) {
      background-image: linear-gradient(
          rgba(47, 48, 58, 0.4),
          rgba(47, 48, 58, 0.4)
        ),
        url(../image/hero-m-x2-min.jpg);
      background-size: cover;
    }
  }
  @media screen and (min-width: 760px) {
    padding-top: 118px;
    padding-bottom: 118px;
    background-image: linear-gradient(
rgba(47, 48, 58, 0.4), 
rgba(47, 48, 58, 0.4)), url(../image/hero-t-x1-min.jpg);
    @media (min-device-pixel-ratio: 2),
      (min-resolution: 192dpi),
      (min-resolution: 2dppx) {
      background-image:linear-gradient(
rgba(47, 48, 58, 0.4), 
rgba(47, 48, 58, 0.4)), url(../image/hero-t-x2-min.jpg);
      background-size: cover;
    }
  }
  @media screen and (min-width: 1200px) {
    padding-top: 200px;
    padding-bottom: 200px;
    background-image:linear-gradient(
rgba(47, 48, 58, 0.4), 
rgba(47, 48, 58, 0.4)), url(../image/hero-p-x1-min.jpg);
    @media (min-device-pixel-ratio: 2),
      (min-resolution: 192dpi),
      (min-resolution: 2dppx) {
      background-image: linear-gradient(
rgba(47, 48, 58, 0.4), 
rgba(47, 48, 58, 0.4)),url(../image/hero-p-x2-min.jpg);
      background-size: cover;
    }
  }
}
