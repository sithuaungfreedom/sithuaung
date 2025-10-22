မြန်မာ့အလုပ်သမားရေးရာ AI (Myanmar Labour Insight AI)

ဤသည်မှာ မြန်မာနိုင်ငံ၏ အလုပ်သမားရေးရာ ကိစ္စရပ်များ၊ ဥပဒေများ၊ နှင့် အခွင့်အရေးများအကြောင်း မေးမြန်းနိုင်သော AI Chat Application တစ်ခု ဖြစ်ပါသည်။ ဤ project ကို Google ၏ Gemini AI Model (gemini-2.5-flash-preview-09-2025) ကို အသုံးပြု၍ တည်ဆောက်ထားပြီး၊ AI အား မြန်မာ့အလုပ်သမားရေးရာ ကျွမ်းကျင်သူ "Myanmar Labour Insight" အဖြစ် persona သတ်မှတ်ပေးထားပါသည်။

Project ၏ အဓိက လုပ်ဆောင်ချက်များ

Chat Interface: အသုံးပြုသူများ မေးခွန်းမေးမြန်းနိုင်ရန် ရိုးရှင်းလွယ်ကူသော chat window။

AI Persona: AI သည် အလုပ်သမားရေးရာ ကျွမ်းကျင်သူအဖြစ် သီးသန့် ဖြေကြားပေးမည်ဖြစ်ပြီး၊ ဘက်မလိုက်သော၊ တိကျသော အချက်အလက်များကို ဥပဒေပုဒ်မများ၊ အစီရင်ခံစာများဖြင့် ကိုးကား ဖြေကြားပေးပါမည်။

Markdown Support: AI ၏ အဖြေများတွင် စာလုံးထူ၊ စာလုံးစောင်း များကို ရှင်းလင်းစွာ ပြသပေးနိုင်သည်။

Single File: index.html ဖိုင်တစ်ခုတည်းဖြင့် HTML, Tailwind CSS, နှင့် JavaScript ทั้งหมดကို ပေါင်းစပ်ထားသောကြောင့် အလွယ်တကူ run နိုင်သည်။

အသုံးပြုနည်း (How to Use)

ဤ App ကို သင်ကိုယ်တိုင် run နိုင်ရန် အဆင့် (၃) ဆင့် လိုအပ်ပါသည်-

အဆင့် ၁: Google AI Studio မှ API Key ရယူခြင်း

Google AI Studio Website သို့ သွားပါ။

သင်၏ Google Account ဖြင့် Login ဝင်ပါ။

Create API key (သို့မဟုတ် Get API key) ကိုနှိပ်ပြီး API Key အသစ်တစ်ခု ဖန်တီးပါ။

အဆင့် ၂: API Key ကို Code ထဲသို့ ထည့်သွင်းခြင်း

ဤ project မှ index.html ဖိုင်ကို Text Editor (ဥပမာ - VS Code, Notepad++) ဖြင့် ဖွင့်ပါ။

JavaScript အပိုင်း ( <script> tag အတွင်း) ရှိ အောက်ပါနေရာကို ရှာပါ။

// --- AI Configuration ---
const API_KEY = "YOUR_API_KEY_HERE"; // <--- ဤနေရာတွင် ကူးထည့်ပါ။


"YOUR_API_KEY_HERE" နေရာတွင် သင်ရရှိလာသော API Key ကို အစားထိုး ကူးထည့်ပါ။

အဆင့် ၃: Browser တွင် ဖွင့်ခြင်း

index.html ဖိုင်ကို save လုပ်ပြီး၊ သင်အသုံးပြုနေကျ Web Browser (Chrome, Firefox, Edge) ဖြင့် ဖွင့်လိုက်သည်နှင့် AI Chat App ကို စတင် အသုံးပြုနိုင်ပါပြီ။

အရေးကြီးသော သတိပေးချက် (Disclaimer)

ဤ project သည် သင်ကြားလေ့လာရန်နှင့် စမ်းသပ်ရန် (Development & Testing) အတွက်သာ ဖြစ်ပါသည်။ API Key ကို index.html ဖိုင်ထဲတွင် တိုက်ရိုက် ထည့်သွင်းထားခြင်း (Hardcoding) သည် လုံခြုံရေးအရ အန္တရာယ်ရှိပါသည်။

အကယ်၍ ဤ project ကို အများပြည်သူသုံးမည့် Website အဖြစ် တရားဝင် တင်မည်ဆိုပါက၊ API Key ကို Backend (Server) ပေါ်တွင် လုံခြုံစွာ သိမ်းဆည်းပြီး၊ Frontend မှ Backend ကို ခေါ်ဆိုသည့် နည်းလမ်း (Server-side implementation) ကို မဖြစ်မနေ အသုံးပြုသင့်ပါသည်။
