(function () {
    var front  = ".";
    var back = ".";

    var apis = {
        master: {
            hostname: front,
            api: front + "/fo"
        },
        
        // this should be commented out if only one server FO or BO
        back: {
            hostname: back,
            api: back + "/bo"
        }
    }


    window.cassioPosConfig = {
        hostname: apis.master.hostname,
        apis: apis,
        masterApi : 'master', //api which manage session and userconfiguration
		security: true,
		// reCaptchaSiteKey: "xxx",
		// reCaptchaSecretKey: "yyy",
         loginLogoImg : 'img/login/logo_login_sbs.png', //allow to switch login page logo or replace img/login/logo_login.png
        // loginBackgroundImg : 'img/login/bg_login.jpg', //allow to switch background image or replace img/login/bg_login.png
        // loginBackgroundColor : '#dd4b39' // allow to override background by a color
    };

})();