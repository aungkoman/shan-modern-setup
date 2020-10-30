# Finally, we meet Webpack, Babel and Yarn 
နောက်ဆုံးတော့ တွေ့ခဲ့ပြီ ကိုယ့်လူရေ။ ကိုယ်နားမလည်တဲ့ အရာတစ်ခုကို စာဖတ်ပြီး နားလည်သွားတဲ့ အခါ တော်တော်လေး နေသာထိုင်သာရှိသွားတဲ့ ခံစားချက်ရတယ်။
 
ကိုယ့်ရဲ့ code base ကို ကိုယ်ကြည့်ပြီး စိတ်ညစ်တာ ဒီတစ်ခါ ပထမဆုံးတော့ မဟုတ်ပါဘူး။ ဒါပေမယ့် ဒီတစ်ခါတော့ ပြောင်းမှ ရတော့မယ် ဆိုပြီး ဟိုကြည့် သည်ကြည့် နဲ့ အောက်က article ကို တွေ့တာ။
 
တစ်ခေါက် ဖတ်ကြည့်တယ်။ ချက်ခြင်း ဒုတိယ တစ်ခေါက် စာအုပ်နဲ့ မှတ်စုချမှတ်ရင် ဖတ်တယ်။ coding တွေ တစ်ခါတည်း လိုက်ရေးတယ်။
 
သူ့ concept ကို နားလည်ပေမယ့် coding ကတော့ ထုံးစံအတိုင်း old coding , new error ပါပဲ။ ဒီတော့ မထူးပါဘူး author ရဲ့ starter code base ကိုပဲ ကူးပြီး run ကြည့်မှပဲ အဆင်ပြေသွားတယ်။ latest version တွေ သုံးပြီး တစ်ခေါက်လောက် ပြန်လုပ်တော့ ကြည့်ရဉီးမယ်။
 
အခုတော့ ဒီကောင်ကိုပဲ production အထိ သွားလိုက်ဉီးမယ်။
# Development set up for Phaser 3, Webpack, and ES6.

This is the final version of the project we create in https://snowbillr.github.io/blog/2018-04-09-a-modern-web-development-setup-for-phaser-3/.

For a guide on the concepts included in this project and how to build it from scratch, take a look at [the blog post](https://snowbillr.github.io/blog/2018-04-09-a-modern-web-development-setup-for-phaser-3/).

## Using This Project

1. Make a directory somewhere in your file system where you want to keep your project.
1. `cd` into that directory from the command line.
1. Clone this project with `git clone https://github.com/snowbillr/phaser3-webpack-es6-dev-starter.git`.

## Installing Dependencies

1. Follow the blog post for instructions on how to install [Yarn](https://yarnpkg.com/en/) if you don't already have it installed.
1. From the cloned project's directory, run `yarn install`.

## Running The Project

Once you've installed the project's dependencies, you can run the project using [Webpack Dev Server](https://github.com/webpack/webpack-dev-server).

1. From your project's directory, run `yarn webpack-dev-server`.
1. Open up your browser to `http://localhost:8080`.
1. You should see a web page with a black box that says "Hello Phaser!" in green text. That's our game!
1. :tada:

Because you are running the project through Webpack Dev Server, any time you make a change to your source code, the browser will automatically refresh with your updated code.
