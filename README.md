# TaxC
Making Tax processing easy in Bangladesh
# Tax Payment Web Application

A complete full-stack tax payment system built with React.js (frontend) and Flask (backend).

## 🚀 Quick Start

### Backend Server (Running ✅)
```bash
cd backend
python app.py
```
- Server:  http://localhost:5000
- Status: ✅ Running

### Frontend (Setup Complete, Pages Need Implementation)
```bash
cd frontend
npm run dev
```

## 🔐 Default Login
- **Admin**: admin@tax.com / admin123

## 📚 Features (All 10 Implemented in Backend)

1. ✅ User Authentication (Session-based)
2. ✅ Taxpayer Profile Management  
3. ✅ Income Input & Tax Form Submission
4. ✅ Automated Tax Calculation Engine
5. ✅ Tax Payment Simulation
6. ✅ PDF Receipt Generation
7. ✅ Admin Dashboard
8. ✅ Tax Slab Management
9. ✅ User Management
10. ✅ AI Chatbot (Rule-based + API ready)

## 📖 Documentation

See [walkthrough.md](file:///C:/Users/hp/.gemini/antigravity/brain/5e39518a-46e1-4971-a60e-22a4fb5e8f6d/walkthrough.md) for complete documentation.

## 🧪 Test Backend API

```bash
# Health Check
curl http://localhost:5000/api/health

# Calculate Tax
curl -X POST http://localhost:5000/api/tax/calculate \
  -H "Content-Type: application/json" \
  -d "{\"annual_income\":500000}"

# View Tax Slabs
curl http://localhost:5000/api/tax/slabs
```

## 📁 Project Structure

- **backend/** - Complete Flask API with all 10 features ✅
- **frontend/** - React app (services ready, pages pending)

## 🎯 Next Steps

1. Implement React pages (Login, Dashboard, Profile, etc.)
2. Connect frontend to backend APIs
3. Test end-to-end flows
4. Add your AI chatbot API key to `.env`
