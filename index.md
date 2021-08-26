QA LINK BUILDER

<html>

<head>

  <title>SUBMIT QA DETAILS</title>

  <!-- <style>
    table#placementTable {
      width: 95%;
      margin: 0 auto;
    }
    table#placementTable th,
    table#placementTable td {
      font-weight: normal;
      font-size: 12px;
    }
  </style> -->
</head>

<body>
  <!-- Sign In Modal Trigger -->
  <a id="signInModal" style="display:none" class="waves-effect waves-light btn modal-trigger signInModal" href="#modalInitial">Modal</a>

  <!-- Modal Structure -->
  <div id="modalInitial" class="modal">
    <a id="closeModal" style="display:none" class="waves-effect waves-teal btn-flat right modal-close"><i class="material-icons">close</i></a>
    <div class="modal-content">
      <h4>ONLINE TS</h4>
      <p>Please click the "signin" button below to login using your work google account credentials. Thanks!</p>
    </div>
    <div class="modal-footer">
      <a id="signinOnLoad" class="waves-effect waves-light btn" onclick="handleSignInClick()">SIGN IN</a>
    </div>
  </div>
  <!-- <blockquote>LINK BUILDER FORM</blockquote> -->

  <!-- Modal Trigger -->
  <a id="modal-trigger" style="display:none" class="waves-effect waves-light btn modal-trigger" href="#modal1">Modal</a>
  <div id="modal1" class="modal">
    <a id="closeModal" class="waves-effect waves-teal btn-flat right modal-close"><i class="material-icons">close</i></a>
    <div class="modal-content">
      <!-- <h4>OOPS! You probably missed something!</h4> -->
      <p id="modal1text"></p>
    </div>
    <div class="modal-footer">

    </div>
  </div>
  <div class="row container left">

    </div>
    <fieldset class="fieldSetForm" id="displayPlacementNamesFS" style="border: 0;">
      <div id="displayPlacementNames">
        <div id="campaignDetails" class="col s11">
          <!--YOURNAME-->
          <h6>YOUR NAME</h6>
          <div class="row input-field col s12">
            <i class="material-icons prefix">account_circle</i>
            <input id="requester" style="text-transform: uppercase" type="text" class="validate tooltipped" data-position="right" data-tooltip="Please enter your name.">
          </div>
          <!--COUNTRY-->
          <h6>COUNTRY</h6>
            <div class="row input-field col s12">
            <i class="material-icons prefix">account_circle</i>
            <input id="requester" style="text-transform: uppercase" type="text" class="validate tooltipped" data-position="right" data-tooltip="Please enter country code.">
          </div>
          <!--SIGNAL ID-->
          <h6>SIGNAL ID</h6>
            <div class="row input-field col s12">
            <i class="material-icons prefix">account_circle</i>
            <input id="requester" style="text-transform: uppercase" type="text" class="validate tooltipped" data-position="right" data-tooltip="Please enter signal id.">
          </div>
          <!--WID-->
          <h6>WID</h6>
            <div class="row input-field col s12">
            <i class="material-icons prefix">account_circle</i>
            <input id="requester" style="text-transform: uppercase" type="text" class="validate tooltipped" data-position="right" data-tooltip="Please enter wid.">
          </div>
          <!--DEVICE ID-->
          <h6>DEVICE ID</h6>
            <div class="row input-field col s12">
            <i class="material-icons prefix">account_circle</i>
            <input id="requester" style="text-transform: uppercase" type="text" class="validate tooltipped" data-position="right" data-tooltip="Please enter device id.">
          </div>
          <!--GEO-->
          <h6>GEO</h6>
            <div class="row input-field col s12">
            <i class="material-icons prefix">account_circle</i>
            <input id="requester" style="text-transform: uppercase" type="text" class="validate tooltipped" data-position="right" data-tooltip="Please enter country code.">
          </div>
          <!--APP ID-->
          <h6>APP ID</h6>
            <div class="row input-field col s12">
            <i class="material-icons prefix">account_circle</i>
            <input id="requester" style="text-transform: uppercase" type="text" class="validate tooltipped" data-position="right" data-tooltip="Please enter app id.">
          </div>
        </div>
          <!--PLATFORM-->
          <h6>PLATFORM</h6>
            <div class="row input-field col s12">
            <i class="material-icons prefix">account_circle</i>
            <input id="requester" style="text-transform: uppercase" type="text" class="validate tooltipped" data-position="right" data-tooltip="Please iOS, Web or Android.">
        </div>
                  <!--REFERRER-->
          <h6>REFERRER</h6>
            <div class="row input-field col s12">
            <i class="material-icons prefix">account_circle</i>
            <input id="requester" style="text-transform: uppercase" type="text" class="validate tooltipped" data-position="right" data-tooltip="Please Pokerstars, Pokerstars Casino or Pokerstars Sports.">
        </div>
  <script async defer src="https://apis.google.com/js/api.js" onload="this.onload=function(){};handleClientLoad()" onreadystatechange="if (this.readyState === 'complete') this.onload()">
