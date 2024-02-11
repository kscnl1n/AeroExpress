<template>
  <div class="aero-interaction">
    <div class="div-2">
      <div class="overlap">
        <div class="overlap-group">
          <div class="group">
            <div class="overlap-group-2">
              <div class="rectangle" />
              <div class="rectangle-2" />
            </div>
          </div>
          <div class="overlap-wrapper">
            <div class="overlap-2">
              <div class="group-2">
                <div class="overlap-group-wrapper">
                  <div class="overlap-group-3">
                    <div class="ellipse" />
                    <img class="icon-person" alt="Icon person" src="icon-person.png" />
                  </div>
                </div>
                <div class="rectangle-3" />
              </div>
              <p class="p">Hey Aero, could you get me the fastest flight from IAH to LAX at the lowest cost?</p>
            </div>
          </div>
          <div class="div-wrapper">
            <div class="overlap-3">
              <div class="group-3">
                <div class="group-4">
                  <div class="overlap-group-4">
                    <div class="ellipse-2" />
                    <img class="img" alt="Icon person" src="image.png" />
                  </div>
                </div>
                <div class="rectangle-4" />
              </div>
              <p class="text-wrapper-4">This is perfect Aero, Thanks!</p>
            </div>
          </div>
          <div class="group-5">
            <div class="overlap-4">
              <div class="rectangle-5" />
              <div class="text-wrapper-5">You’re very welcome!</div>
            </div>
            <div class="untitled">
              <router-link to="/aero-interaction-page">
                <img class="untitled-2" alt="Untitled" src="untitled-1.png" />
              </router-link>
            </div>
          </div>
          <div class="group-6">
            <div class="untitled-wrapper">
              <router-link to="/aero-interaction-page">
                <img class="untitled-2" alt="Untitled" src="untitled-1-2.png" />
              </router-link>
            </div>
            <div class="group-7">
              <div class="overlap-group-5">
                <div class="rectangle-6" />
                <p class="text-wrapper-6">
                  Certainly Ruben! Here are three of the fastest flights from IAH to LAX in order of price lowest to
                  highest.
                </p>
              </div>
            </div>
            <div class="group-8">
              <div class="departing-mar-wrapper">
                <p class="departing-mar">
                  <span class="span">
                    Departing Mar 10th: <br />
                  </span>
                  <span class="text-wrapper-7">
                    IAH to LAX 3h 50m | $125
                    <br />
                    IAH to LAX 3h 50m | $196
                    <br />
                    IAH to LAX 5h 40m | $206
                  </span>
                </p>
              </div>
            </div>
          </div>
          <div class="group-9">
            <div class="overlap-5">
              <div class="img-wrapper">
                <router-link to="/aero-interaction-page">
                  <img class="untitled-3" alt="Untitled" src="untitled-1-3.png" />
                </router-link>
              </div>
              <img class="icon-mic" alt="Icon mic" src="icon-mic.png" />
            </div>
          </div>
        </div>
        <Asset class="asset-2-1" />
        <img class="PROS-logo-AI-FA" alt="Pros logo AI FA" src="PROS-logo-AI-FA-v1r5-1c-rev-300x62-1.png" />
      </div>
      <div class="overlap-6">
        <Asset class="asset-instance" />
        <Home class="home-instance" />
        <StartTalking class="start-talking-instance" />
        <LogIn class="log-in-instance" />
        <SignUp class="sign-up-instance" />
        <div class="group-10">
          <div class="overlap-7">
            <div class="ellipse-3" />
            <img class="icon-person-2" alt="Icon person" src="icon-person-2.png" />
          </div>
        </div>
        <div class="group-11">
          <div class="overlap-8">
            <p class="text-wrapper-8">Start looking for flights now</p>
            <img class="vector" alt="Vector" src="vector.svg" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import { Asset } from "./Asset";
import { Home } from "./Home";
import { LogIn } from "./LogIn";
import { SignUp } from "./SignUp";
import { StartTalking } from "./StartTalking";

export default {
  name: "AeroInteraction",
  components: {
    Asset,
    Home,
    LogIn,
    SignUp,
    StartTalking,
  },
};
</script>

<style>
.aero-interaction {
  background-color: #ffffff;
  display: flex;
  flex-direction: row;
  justify-content: center;
  width: 100%;
}

.aero-interaction .div-2 {
  background-color: #ffffff;
  height: 1472px;
  position: relative;
  width: 1440px;
}

.aero-interaction .overlap {
  background-image: url(./pexels-sevenstorm-juhaszimrus-1436697-1.png);
  background-position: 50% 50%;
  background-size: cover;
  height: 1372px;
  left: 0;
  position: absolute;
  top: 100px;
  width: 1440px;
}

.aero-interaction .overlap-group {
  height: 1171px;
  left: 252px;
  position: absolute;
  top: 41px;
  width: 936px;
}

.aero-interaction .group {
  height: 1171px;
  left: 0;
  position: absolute;
  top: 0;
  width: 936px;
}

.aero-interaction .overlap-group-2 {
  height: 1171px;
  position: relative;
}

.aero-interaction .rectangle {
  background-color: var(--d-9d-9d-9);
  border-radius: 55px;
  height: 1171px;
  left: 0;
  position: absolute;
  top: 0;
  width: 880px;
}

.aero-interaction .rectangle-2 {
  background-color: var(--d-9d-9d-9);
  border-radius: 55px;
  height: 1171px;
  left: 56px;
  position: absolute;
  top: 0;
  width: 880px;
}

.aero-interaction .overlap-wrapper {
  height: 171px;
  left: 259px;
  position: absolute;
  top: 52px;
  width: 638px;
}

.aero-interaction .overlap-2 {
  height: 171px;
  position: relative;
  width: 636px;
}

.aero-interaction .group-2 {
  height: 168px;
  left: 0;
  position: absolute;
  top: 0;
  width: 636px;
}

.aero-interaction .overlap-group-wrapper {
  height: 111px;
  left: 543px;
  position: absolute;
  top: 5px;
  width: 93px;
}

.aero-interaction .overlap-group-3 {
  height: 111px;
  position: relative;
}

.aero-interaction .ellipse {
  background-color: #d9d9d9;
  border-radius: 46.55px;
  height: 93px;
  left: 0;
  position: absolute;
  top: 0;
  width: 93px;
}

.aero-interaction .icon-person {
  height: 96px;
  left: 6px;
  position: absolute;
  top: 15px;
  width: 82px;
}

.aero-interaction .rectangle-3 {
  background-color: #d9d9d9;
  border-radius: 55px;
  height: 168px;
  left: 0;
  position: absolute;
  top: 0;
  width: 526px;
}

.aero-interaction .p {
  color: #000000;
  font-family: "Roboto-Regular", Helvetica;
  font-size: 32px;
  font-weight: 400;
  height: 168px;
  left: 46px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 3px;
  width: 433px;
}

.aero-interaction .div-wrapper {
  height: 134px;
  left: 259px;
  position: absolute;
  top: 728px;
  width: 637px;
}

.aero-interaction .overlap-3 {
  height: 134px;
  position: relative;
  width: 635px;
}

.aero-interaction .group-3 {
  height: 134px;
  left: 0;
  position: absolute;
  top: 0;
  width: 635px;
}

.aero-interaction .group-4 {
  height: 134px;
  left: 542px;
  position: absolute;
  top: 0;
  width: 93px;
}

.aero-interaction .overlap-group-4 {
  height: 134px;
  position: relative;
}

.aero-interaction .ellipse-2 {
  background-color: #d9d9d9;
  border-radius: 46.5px;
  height: 93px;
  left: 0;
  position: absolute;
  top: 0;
  width: 93px;
}

.aero-interaction .img {
  height: 118px;
  left: 6px;
  position: absolute;
  top: 16px;
  width: 82px;
}

.aero-interaction .rectangle-4 {
  background-color: #d9d9d9;
  border-radius: 55px;
  height: 111px;
  left: 0;
  position: absolute;
  top: 0;
  width: 526px;
}

.aero-interaction .text-wrapper-4 {
  color: #000000;
  font-family: "Roboto-Regular", Helvetica;
  font-size: 32px;
  font-weight: 400;
  height: 110px;
  left: 41px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 4px;
  width: 433px;
}

.aero-interaction .group-5 {
  height: 101px;
  left: 41px;
  position: absolute;
  top: 892px;
  width: 661px;
}

.aero-interaction .overlap-4 {
  height: 101px;
  left: 133px;
  position: absolute;
  top: 0;
  width: 526px;
}

.aero-interaction .rectangle-5 {
  background-color: var(--pros-ulb);
  border-radius: 55px;
  height: 100px;
  left: 0;
  position: absolute;
  top: 1px;
  width: 526px;
}

.aero-interaction .text-wrapper-5 {
  color: #000000;
  font-family: "Roboto-Regular", Helvetica;
  font-size: 32px;
  font-weight: 400;
  height: 101px;
  left: 41px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 0;
  width: 433px;
}

.aero-interaction .untitled {
  height: 100px;
  left: 0;
  position: absolute;
  top: 1px;
  width: 131px;
}

.aero-interaction .untitled-2 {
  display: block;
  height: 100px;
  left: 0;
  object-fit: cover;
  position: absolute;
  top: 0;
  width: 131px;
}

.aero-interaction .group-6 {
  height: 405px;
  left: 41px;
  position: absolute;
  top: 273px;
  width: 659px;
}

.aero-interaction .untitled-wrapper {
  height: 100px;
  left: 0;
  position: absolute;
  top: 0;
  width: 131px;
}

.aero-interaction .group-7 {
  height: 191px;
  left: 133px;
  position: absolute;
  top: 0;
  width: 528px;
}

.aero-interaction .overlap-group-5 {
  height: 191px;
  position: relative;
  width: 526px;
}

.aero-interaction .rectangle-6 {
  background-color: var(--pros-ulb);
  border-radius: 55px;
  height: 188px;
  left: 0;
  position: absolute;
  top: 0;
  width: 526px;
}

.aero-interaction .text-wrapper-6 {
  color: #000000;
  font-family: "Roboto-Regular", Helvetica;
  font-size: 32px;
  font-weight: 400;
  height: 183px;
  left: 41px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 8px;
  width: 433px;
}

.aero-interaction .group-8 {
  height: 201px;
  left: 128px;
  position: absolute;
  top: 204px;
  width: 528px;
}

.aero-interaction .departing-mar-wrapper {
  background-color: var(--pros-ulb);
  border-radius: 55px;
  height: 201px;
  position: relative;
  width: 526px;
}

.aero-interaction .departing-mar {
  color: transparent;
  font-family: "Roboto-Regular", Helvetica;
  font-size: 32px;
  font-weight: 400;
  height: 192px;
  left: 46px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 4px;
  width: 433px;
}

.aero-interaction .span {
  color: #000000;
}

.aero-interaction .text-wrapper-7 {
  color: #034c7d;
  text-decoration: underline;
}

.aero-interaction .group-9 {
  height: 139px;
  left: 377px;
  position: absolute;
  top: 1027px;
  width: 182px;
}

.aero-interaction .overlap-5 {
  height: 139px;
  position: relative;
}

.aero-interaction .img-wrapper {
  height: 139px;
  left: 0;
  position: absolute;
  top: 0;
  width: 182px;
}

.aero-interaction .untitled-3 {
  display: block;
  height: 139px;
  left: 0;
  object-fit: cover;
  position: absolute;
  top: 0;
  width: 182px;
}

.aero-interaction .icon-mic {
  height: 91px;
  left: 50px;
  position: absolute;
  top: 29px;
  width: 84px;
}

.aero-interaction .asset-2-1 {
  background-image: url(./asset-2-1-3.png) !important;
  left: 156px !important;
  position: absolute !important;
  top: 1267px !important;
}

.aero-interaction .PROS-logo-AI-FA {
  height: 67px;
  left: 1092px;
  object-fit: cover;
  position: absolute;
  top: 1267px;
  width: 320px;
}

.aero-interaction .overlap-6 {
  background-color: var(--pros-light-blue);
  height: 100px;
  left: 0;
  position: absolute;
  top: 0;
  width: 1440px;
}

.aero-interaction .asset-instance {
  background-image: url(./asset-2-1-2.png) !important;
  left: 156px !important;
  position: absolute !important;
  top: 17px !important;
}

.aero-interaction .home-instance {
  left: 827px !important;
  position: absolute !important;
  top: 34px !important;
}

.aero-interaction .start-talking-instance {
  left: 928px !important;
  position: absolute !important;
  top: 34px !important;
}

.aero-interaction .log-in-instance {
  left: 1101px !important;
  position: absolute !important;
  top: 34px !important;
}

.aero-interaction .sign-up-instance {
  left: 1203px !important;
  position: absolute !important;
  top: 34px !important;
}

.aero-interaction .group-10 {
  height: 72px;
  left: 1316px;
  position: absolute;
  top: 16px;
  width: 69px;
}

.aero-interaction .overlap-7 {
  height: 72px;
  position: relative;
}

.aero-interaction .ellipse-3 {
  background-color: #d9d9d9;
  border-radius: 34.45px;
  height: 69px;
  left: 0;
  position: absolute;
  top: 0;
  width: 69px;
}

.aero-interaction .icon-person-2 {
  height: 66px;
  left: 4px;
  position: absolute;
  top: 6px;
  width: 61px;
}

.aero-interaction .group-11 {
  height: 46px;
  left: 284px;
  position: absolute;
  top: 28px;
  width: 513px;
}

.aero-interaction .overlap-8 {
  background-color: var(--pros-ulb);
  border-radius: 100px;
  height: 46px;
  position: relative;
  width: 511px;
}

.aero-interaction .text-wrapper-8 {
  color: #30303099;
  font-family: "Roboto-Regular", Helvetica;
  font-size: 24px;
  font-weight: 400;
  height: 46px;
  left: 67px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 0;
  width: 410px;
}

.aero-interaction .vector {
  height: 32px;
  left: 23px;
  position: absolute;
  top: 11px;
  width: 30px;
}
</style>