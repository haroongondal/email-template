<template>
  <div class="email">
    <center class="email__wrapper">
      <table class="email__main" width="80%">
        <tr>
          <td style="padding:10px 10px 10px">
            <table width="100px" class="email__main__column">
              <tr>
                <td class="email__main__logo">
                  <img
                    src="../assets/email/1. Final Logo Baskyt@3x.png"
                    alt="baskyt logo"
                  />
                </td>
              </tr>
            </table>
          </td>
        </tr>
        <tr>
          <td>
            <table width="100%" class="email__main__block email__main__column">
              <tr>
                <td>
                  <table class="email__main__column">
                    <tr>
                      <td>
                        <p
                          style="font-size:25px;padding-top:40px;padding-bottom:16px"
                        >
                          <strong>Welcome to Baskyt</strong>
                        </p>
                      </td>
                    </tr>
                    <tr>
                      <td>
                        <img
                          width="250"
                          src="../assets/email/Group 8385@3x.png"
                          alt=""
                        />
                      </td>
                    </tr>
                    <tr>
                      <td>
                        <p
                          style="font-size:18px;padding-top:26px;font-weight:bolder"
                        >
                          Hi Adam,
                        </p>
                      </td>
                    </tr>
                    <tr>
                      <td>
                        <p
                          style="font-size:16px;padding-top:12px;text-align:left;margin-bottom:0px;font-weight:bolder"
                        >
                          Welcome to Baskyt!
                        </p>
                      </td>
                    </tr>
                    <tr>
                      <td>
                        <p
                          style="font-size:16px;padding-top:12px;text-align:left;font-weight:bolder"
                        >
                          Click on the link below to start your onboarding
                          process.
                        </p>
                      </td>
                    </tr>
                    <tr>
                      <td style="padding-top:10px;padding-bottom:30px">
                        <a
                          class="email__main__button--solid"
                          href="http://www.baskytinc.com"
                          >Start Onboarding</a
                        >
                      </td>
                    </tr>
                    <tr>
                      <td>
                        <p
                          style="font-size:16px;padding-top:20px;text-align:left;margin-bottom:0px;font-weight:bolder"
                        >
                          Best of luck
                        </p>
                      </td>
                    </tr>
                    <tr>
                      <td>
                        <p
                          style="font-size:16px;padding-top:6px;text-align:left;margin-bottom:0;font-weight:bolder"
                        >
                          OnBoarding Team
                        </p>
                      </td>
                    </tr>
                    <tr>
                      <td>
                        <p
                          style="font-size:16px;padding-top:6px;text-align:left;font-weight:bolder"
                        >
                          Baskyt, Inc.
                        </p>
                      </td>
                    </tr>
                  </table>
                </td>
              </tr>
            </table>
          </td>
        </tr>

        <tr>
          <td>
            <table
              class="email__main__block "
              style="margin-top:48px;width:100%"
            >
              <tr class="email__main__column  " style="padding-top:16px">
                <td>
                  <p
                    style="font-size:18px;color:black;margin-bottom:0px;padding-top:16px;font-weight:bolder"
                  >
                    Have any Questions?
                  </p>
                </td>
              </tr>
              <tr class="email__main__column">
                <td>
                  <p
                    style="font-size:13px;color:gray;margin-bottom:0px;padding-top:10px;font-weight:bolder"
                  >
                    Email us your queries at
                    <span style="color:#EC2E35">info@baskytinc.com</span>
                  </p>
                </td>
              </tr>
              <tr class="email__main__column ">
                <td>
                  <p
                    style="font-size:13px;color:gray;margin-bottom:12px;font-weight:bolder"
                  >
                    or call at <span style="color:#EC2E35">(952) 456-4102</span>
                  </p>
                </td>
              </tr>
            </table>
          </td>
        </tr>
      </table>

      <table class=" email__main email__footer">
        <tr>
          <td>
            <table class="email__main__column" width="50%">
              <tr>
                <td>
                  <p
                    style="font-size:12px;color:white;padding-top:16px;margin-bottom:0px"
                  >
                    Follow Us
                  </p>
                </td>
              </tr>
              <tr>
                <td>
                  <a
                    style="
            margin-left:16px"
                  >
                    href="https://www.facebook.com" ><img
                      width="20px"
                      src="../assets/social/facebook.png"
                      alt="facebook"
                  /></a>
                  <a
                    style="
            margin-left:16px"
                    href="https://www.twitter.com"
                    ><img
                      width="20px"
                      src="../assets/social/twitter.png"
                      alt="twitter"
                  /></a>
                  <a
                    style="
            margin-left:16px"
                    href="https://www.linkedin.com"
                    ><img
                      width="20px"
                      src="../assets/social/linkedin.png"
                      alt="linkedin"
                  /></a>
                  <a
                    style="
            margin-left:16px"
                    href="https://www.instagram.com"
                    ><img
                      width="20px"
                      src="../assets/social/instagram.png"
                      alt="instagram"
                  /></a>
                </td>
              </tr>
              <tr>
                <td>
                  <hr
                    class="email__main__line"
                    style="margin-top:16px;margin-bottom:16px"
                  />
                </td>
              </tr>
              <tr>
                <td style="padding-bottom:16px">
                  <span class="email__main email__footer__links">FAQs</span>
                  <span class="email__main email__footer__links"
                    >Privacy Policy</span
                  >
                  <span class="email__main email__footer__links"
                    >Terms and Conditions</span
                  >
                  <span
                    class="email__main email__footer__links"
                    style="border:none"
                    >Unsubscribe</span
                  >
                </td>
              </tr>
            </table>
          </td>
        </tr>
      </table>
    </center>
  </div>
</template>

<script>
export default {
  name: "emailDelivered"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
@import url("https://fonts.googleapis.com/css2?family=Roboto:wght@100;300&display=swap");
.email {
  font-family: "Roboto", sans-serif;
  margin: 0;
  background-color: #cccccc;

  table {
    border-spacing: 0;
    td {
      padding: 0;
      border: none;
    }
    tr {
      padding: 0;
    }
    p {
      margin-top: 0;
    }
  }
  &__wrapper {
    width: 100%;
    max-width: 600px;
    background-color: #ffffff;

    table-layout: fixed;
  }
  &__main {
    margin: 0 auto;
    border-spacing: 0;
    color: #171a1b;
    line-height: 1.5;
    &__social-button {
      // border: 1px solid red;
      border-radius: 10px;
      // padding: 5px 10px;
      p {
        font-size: 12px;
        color: #ec2e35;
      }
    }
    @media (max-width: 992px) {
      width: 90%;
    }
    &__line {
      border-top: 1px solid gray;
      margin-top: 24px;
      margin-bottom: 24px;
    }
    &__bg-img {
      background-image: url(/assets/static-assets/email/BANNER@3x.png);
      // background-size: 300px;
    }
    &__subHeading {
      font-size: 13px;
      color: gray;
      font-weight: bolder;
      margin-bottom: 0px;
    }
    &__heading {
      font-size: 15px;
      color: gray;
      font-weight: bolder;
      margin-bottom: 0px;
      padding-top: 16px;
      padding-bottom: 16px;
    }
    &__block {
      background-color: #eff0f7;
      @media (max-width: 992px) {
        padding-left: 10px !important;
        padding-right: 10px !important;
      }
    }
    &__two-columns {
      font-size: 0;

      &__column {
        display: inline-block;
        vertical-align: top;
        text-align: center;
      }
      &__column--md {
        width: 50%;
        display: inline-block;
        vertical-align: top;
        text-align: center;
        img {
          @media (max-width: 992px) {
            width: 100% !important;
          }
        }
        @media (max-width: 992px) {
          width: 100% !important;
          margin-top: 10px;
          text-align: center;
        }
      }
    }

    &__button--solid {
      border: 1px solid #ec2e35;
      padding: 8px 20px;
      border-radius: 10px;
      color: white;
      background-color: #ec2e35;
      text-decoration: none;
    }

    &__column {
      text-align: center;
      margin-left: auto;
      margin-right: auto;
    }
    &__logo {
      border-radius: 50%;
      padding: 10px;
      width: 60px;
      height: 60px;
      border: 1px solid gray;
      img {
        // border-radius: 50%;
        width: 40px;
        height: 40px;
      }
    }
  }
  &__footer {
    width: 100% !important;
    background-color: #14182b;
    padding-top: 16px;
    margin-top: 40px;
    &__links {
      color: white;
      font-size: 9px;
      border-right: 1px solid white;
      padding-right: 8px;
      padding-left: 8px;
      padding-top: 0px;
      padding-bottom: 0px;
    }
  }
  img {
    border: 0;
  }
}
</style>
