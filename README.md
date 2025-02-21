Android vs Website: Comparison
Aspect	Android (Baseline Profiles)	Website (Similar Techniques)
Purpose	App startup aur runtime performance	Page load time aur rendering speed
Tool	ART, Gradle, Benchmarks	Lighthouse, Webpack, Service Workers
Output	.prof file	Optimized JS/CSS, cached assets
Execution	Device-side (AOT compilation)	Browser-side ya server-side
Automation	Nightly GitHub Actions	Nightly GitHub Actions possible









-----------------------------------------------------------
Android Mein: Baseline Profiles ek specific feature hai jo sirf Android apps ke liye hai, kyunki yeh ART ke saath kaam karta hai.
Websites Mein: Direct Baseline Profiles nahi hote, lekin similar optimization techniques (Critical CSS, WebAssembly, etc.) use hoti hain. Inko "Baseline Profiles" ki tarah automate karna possible hai with tools like Lighthouse aur GitHub Actions.
Fark: Android ka focus device-specific compilation pe hai, jabki websites ka browser compatibility aur network pe.
Agar aap website ke liye koi specific optimization workflow banane mein help chahiye, to batana! Ya






----------------------------------------------------------------
Part	 Kahan Aata Hai	Kyun
name	Shuru mein	Workflow ka naam dikhane ke liye
on	name ke niche	Kab chalega yeh batane ke liye
jobs	 on ke niche	Kaam define karne ke liye
runs-on	Job ke andar	Machine type batane ke liye
steps	Job ke andar	Chhote kaam likhne ke liye
uses	Step mein	Pre-built action call karne ke liye
run	Step mein	Custom command chalane ke liye
with	uses ke saath	Action ko inputs dene ke liye
