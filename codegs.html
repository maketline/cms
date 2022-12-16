// @ts-nocheck
function doGet(e){
  return HtmlService.createTemplateFromFile('index').evaluate()
  .setTitle(details1)
  .addMetaTag('viewport','width=deviec-width,initial-scale=1')
  .setFaviconUrl(favIcon)
  .setXFrameOptionsMode(HtmlService.XFrameOptionsMode.ALLOWALL)
}

/** ***************** Include File *********************** **/
function include(filename) {
  return HtmlService.createHtmlOutputFromFile(filename).getContent();
}

/** ***************** Get URL *********************** **/
function getScriptURL() {
  return ScriptApp.getService().getUrl();
}

/** @ข้อมูลติดต่อเรา*/
function sendcontact(obj) {
  var data = SpreadsheetApp.openById(id).getSheetByName("contact")

  data.appendRow([
    '',
    obj.name,
    obj.email,
    obj.subject,
    obj.message,
  ])
 

  var tokenID = contact_tokenid
  // ชุดการแจ้งเตือนทางไลน์
  var msg1 = "ผู้ติดต่อ:" + obj.name;
  var msg2 = "E-mail :" + obj.email;
  var msg3 = "เรื่องติดต่อ :" + obj.subject;
  var msg4 = "รายละเอียดติดต่อ :" + obj.message;
  let msg = "มีข้อมูลการติดต่อผ่านหน้าเว็บไซต์" 
  + '\n' + msg1 
  + '\n' + msg2 
  + '\n' + msg3
  + '\n' + msg4
  let token = tokenID// ไอดี Token แจ้งไลน์ 
  sendNotify(msg, token)
}

function sendNotify(msg, token) {
  let payloadJson = {
    "message": msg,
  };
  let options = {
    "method": "post",
    "payload": payloadJson,
    "headers": {
      "Authorization": "Bearer " + token
    }
  };
  UrlFetchApp.fetch("https://notify-api.line.me/api/notify", options);
}


/** @subscribe*/
function sendsubscribe(obj) {
  var data = SpreadsheetApp.openById(id).getSheetByName("newsletter")

  data.appendRow([
    '',
    obj.email2,
  ])


}
