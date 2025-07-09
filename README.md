# AIBusters

**Blast away AI fakes**—paste any link (image, article, or video), hit ANALYZE, and see “Likely AI” or “Likely Human.”

---

## 🎯 MVP Features
1. **Single-paste interface**: Big input box + “Analyze” button  
2. **Clear results**: Verdict + confidence % + one-sentence explanation  
3. **History log**: View your last 5 analyses  
4. **Senior-friendly UI**: Large fonts, high contrast, minimal jargon

---

## ⚙️ Tech Stack
- **Frontend**: React PWA (Create React App + PWA template)  
- **Backend**: Serverless function (Vercel/Netlify Functions)  
- **AI Engines**:  
  - OpenAI text classifier (for articles)  
  - Free or open-source deepfake detector (for images/videos)

---

## 🚀 Next Steps
- Scaffold the React PWA and deploy “Hello World”  
- Build “Home → Analyze → Results” flow  
- Wire up `/api/analyze` with AI services  
- Deploy to free hosting (Vercel/Netlify)
