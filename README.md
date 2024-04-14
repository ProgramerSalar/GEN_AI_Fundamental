### what is Transformer:

Transformer in Deep Learning

Transformer models deep learning mein ek pramukh bhoomika nibhate hain, khaas karke natural language processing (NLP) tasks mein. In models ko 2017 mein introduce kiya gaya tha aur ye jaldi se machine learning aur artificial intelligence ke vibhinn tasks mein mahatvapurna ho gaye hain.
Transformer model ka mukhya navachar yah hai ki isme recurrent neural networks (RNNs) ya convolutional neural networks (CNNs) par nirbhar nahi karna padta, jo neural network approaches hain jo kuch significant drawbacks ke saath aate hain. Transformers input sequences ko parallel process karte hain, jo training aur inference ke liye bahut hi efficient hota hai.
Transformers ki ek khaas baat yah hai ki inme koi recurrent units nahi hote, aur isliye inhe pehle ke recurrent neural architectures, jaise ki long short-term memory (LSTM), se kam training time ki jarurat hoti hai.
Transformer model ek neural network hai jo sequential data jaise ki is sentence ke words mein relationships track karke context aur thus meaning seekhta hai. Transformer models ek evolving set of mathematical techniques, jise attention ya self-attention kaha jata hai, ka upyog karte hain, taaki series ke even distant data elements par ek dusre par influence aur depend hone ke subtle ways ko detect kiya ja sake.
Transformers ka use natural language processing aur computer vision ke alawa audio aur multi-modal processing mein bhi kiya jata hai. Isne pre-trained systems, jaise ki generative pre-trained transformers (GPTs) aur BERT (Bidirectional Encoder Representations from Transformers) ke development ko bhi badhava diya hai.
Transformers ke architecture ka main intent ek seq2seq model ko lena aur uske recurrent neural networks ko remove karna hota hai. Transformers attention ko use karke computations ko simultaneously kar sakte hain. Layer outputs ko parallel mein compute kiya ja sakta hai, instead of a series like an RNN. Iske alawa, Transformers distant ya long-range contexts aur dependencies ko capture karne mein saksham hote hain.
Transformers ke architecture mein self-attention ka upyog hota hai, jo neural machine translation ke liye Transformer attention mechanism dwara implement kiya jata hai.
Transformers abhi tak ke sabse shaktishali model classes mein se ek hain aur machine learning mein ek wave of advances ko drive kar rahe hain.

### Attention in Deep Learning
Deep learning mein "attention" ek aisa mechanism hai jo model ko input sequence ke kisi specific part par focus karne ki anumati deta hai. Iska mukhya uddeshya yah hai ki model ko sequence ke har element par barabar dhyan na dene ki jagah, kuch specific elements par adhik focus karne ki anumati de.
Jaise ki hum apne daily life mein kisi specific task par focus karte hain, usi tarah attention mechanism model ko kisi specific task par focus karne ki anumati deta hai. Iska matlab hai ki model ko sequence ke har element par barabar dhyan na dene ki jagah, kuch specific elements par adhik focus karne ki anumati de.
Attention mechanism ka upyog sequence-to-sequence (Seq2Seq) models, jaise ki machine translation, mein kiya jata hai. Yeh models ek input sequence ko ek output sequence mein convert karte hain. Attention mechanism ki madad se, model input sequence ke har element ko output sequence ke har element se jod sakta hai.
Attention mechanism ka ek aur mahatvapurna upyog hai "transformer" models mein, jaise ki BERT (Bidirectional Encoder Representations from Transformers) aur GPT (Generative Pretrained Transformer). In models mein, attention mechanism model ko input data ke different parts ke beech ke sambandh ko samajhne mein madad karta hai.
Udaharan ke liye, agar hum ek sentence ko translate kar rahe hain, to attention mechanism model ko input sentence ke har word ko output sentence ke har word se jodne mein madad karta hai. Isse model ko sentence ke structure aur meaning ko samajhne mein madad milti hai.


### Self-Attention in Deep Learning
Deep learning mein "self-attention" ya "intra-attention" ek aisa mechanism hai jo ek sequence ke har element ko usi sequence ke har other element se compare karta hai, aur iske aadhar par ek weighting system banata hai.
Self-attention mechanism ka mukhya uddeshya yah hai ki model ko sequence ke har element par barabar dhyan na dene ki jagah, kuch specific elements par adhik focus karne ki anumati de.
Self-attention mechanism ka upyog sequence-to-sequence (Seq2Seq) models, jaise ki machine translation, mein kiya jata hai. Yeh models ek input sequence ko ek output sequence mein convert karte hain. Self-attention mechanism ki madad se, model input sequence ke har element ko output sequence ke har element se jod sakta hai.
Self-attention mechanism ka ek aur mahatvapurna upyog hai "transformer" models mein, jaise ki BERT (Bidirectional Encoder Representations from Transformers) aur GPT (Generative Pretrained Transformer). In models mein, self-attention mechanism model ko input data ke different parts ke beech ke sambandh ko samajhne mein madad karta hai.
Udaharan ke liye, agar hum ek sentence ko translate kar rahe hain, to self-attention mechanism model ko input sentence ke har word ko output sentence ke har word se jodne mein madad karta hai. Isse model ko sentence ke structure aur meaning ko samajhne mein madad milti hai.
