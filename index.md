QA LINK BUILDER

<!DOCTYPE html>
<html>

<head>

  <link href='https://fonts.googleapis.com/css?family=Open+Sans:400,300,300italic,400italic,600' rel='stylesheet' type='text/css'>
  <link href="https://fonts.googleapis.com/css?family=Roboto:300,400,500,700" rel="stylesheet">
  <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
  <!-- <script src="https://appsforoffice.microsoft.com/lib/1/hosted/Office.js" type="text/javascript"></script> -->
  <link href='https://fonts.googleapis.com/css?family=Open+Sans:400,300,300italic,400italic,600' rel='stylesheet' type='text/css'>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/xlsx/0.8.0/jszip.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/xlsx/0.8.0/xlsx.js"></script>.
  <script src="https://apis.google.com/js/client.js"></script>
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.7.2/jquery.min.js"></script>

  <!--Import Google Icon Font-->
  <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.0/jquery.min.js"></script>
  <!-- <script src="https://cdn.jsdelivr.net/gh/linways/table-to-excel@v1.0.4/dist/tableToExcel.js"></script> -->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/1.12.4/jquery.js"></script>
  <script src="https://rawgit.com/unconditional/jquery-table2excel/master/src/jquery.table2excel.js"></script>
  <script src="https://cdn.jsdelivr.net/gh/linways/table-to-excel@v1.0.4/dist/tableToExcel.js"></script>

  <!--Import materialize.css-->
  <link type="text/css" rel="stylesheet" href="css/materialize.min.css" media="screen,projection" />
  <!--Let browser know website is optimized for mobile-->
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <script type="text/javascript" src="js\materialize.min.js"></script>
  <script type="text/javascript" src="js\traffickingrequestform.js"></script>
  <script type="text/javascript" src="js\createTSTable.js"></script>
  <script type="text/javascript" src="data\countries.json"></script>
  <script type="text/javascript" src="data\countriesLL.json"></script>
  <script type="text/javascript" src="data\networkNamesList.json"></script>
  <script type="text/javascript" src="data\agencyNamesList.json"></script>
  <script type="text/javascript" src="data\brands.json"></script>
  <script type="text/javascript" src="data\platforms.json"></script>
  <script type="text/javascript" src="data\countries.json"></script>
  <script type="text/javascript" src="data\budgetCodes.json"></script>
  <script type="text/javascript" src="data\platformCodes.json"></script>
  <script type="text/javascript" src="data\buyingPlatforms.json"></script>
  <script type="text/javascript" src="data\brandImages.json"></script>
  <script type="text/javascript" src="data\budgets.json"></script>
  <script type="text/javascript" src="data\kpis.json"></script>
  <script type="text/javascript" src="data\buyingMetrics.json"></script>
  <script type="text/javascript" src="data\dimensionsArr.json"></script>
  <script type="text/javascript" src="data\dimensionsBannerArr.json"></script>
  <script type="text/javascript" src="data\dimensionsVideoArr.json"></script>
  <script type="text/javascript" src="data\advertIdsDCM.json"></script>
  <script type="text/javascript" src="data\siteIdsDCM.json"></script>

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
          </div>
          <!--SIGNAL ID-->
          <h6>SIGNAL ID</h6>
          <div class="row input-field col s12">
          </div>
          <!--WID-->
          <h6>WID</h6>
          <div class="row input-field col s12">
          </div>
          <!--DEVICE ID-->
          <h6>DEVICE ID</h6>
          <div class="row input-field col s12">
          </div>
          <!--GEO-->
          <h6>GEO</h6>
          <div class="row input-field col s12">
          </div>
          <!--APP ID-->
          <h6>APP ID</h6>
          <div class="row input-field col s12">
          </div>
        </div>
        <div id="siteDetails" class="col s12">
          <!--PLATFORM-->
          <h6>PLATFORM/h6>
          <div class="row input-field col s12">
            <i class="material-icons prefix">attach_money</i>
          </div>
          <!--COST-->
          <h6>COST</h6>
        </div>
  </script>
  <script async defer src="https://apis.google.com/js/api.js" onload="this.onload=function(){};handleClientLoad()" onreadystatechange="if (this.readyState === 'complete') this.onload()">
  </script>

</body>

</html>
