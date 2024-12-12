# 🏥 Guru Insurance

Guru Insurance is an intelligent insurance recommendation agent that uses the Anthropic Claude API and Streamlit to provide personalized insurance recommendations based on user profiles.

## 🚀 Features

- 💡 Personalized recommendations based on user profile
- 📊 Real-time comparison of coverage and prices
- ⭐ User ratings and reviews system
- 🤖 Intelligent analysis using Anthropic's Claude
- 📱 Intuitive and responsive interface

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/holasoymalva/guru-seguros.git
cd guru-seguros
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Configure your environment variables:
```bash
# Create a .env file in the project root
ANTHROPIC_API_KEY=your_api_key
```

## 🚀 Usage

1. Run the application:
```bash
streamlit run app.py
```

2. Open your browser at `http://localhost:8501`

3. Complete the form with your personal information:
   - Age
   - Marital status
   - Number of children
   - Monthly income
   - Pre-existing medical conditions
   - Risk activities

4. Receive personalized insurance recommendations based on your profile

## 📁 Project Structure

```
guru-seguros/
├── app.py                 # Main Streamlit application
├── requirements.txt       # Project dependencies
├── .env                  # Environment variables (not included in git)
├── README.md             # This file
├── data/                 # Sample data and configurations
│   └── insurance_data.json
└── utils/                # Utilities and helpers
    ├── __init__.py
    ├── recommender.py    # Recommendation logic
    └── claude_helper.py  # Claude integration functions
```

## 🔧 Configuration

### Environment Variables

Create a `.env` file in the project root with the following variables:

```env
ANTHROPIC_API_KEY=your_api_key
```

### Insurance Configuration

Insurance data is located in `data/insurance_data.json`. You can modify this file to adjust:

- Available insurance types
- Plans and coverage
- Prices
- Included benefits

## 🤝 Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is under the MIT License - see the [LICENSE](LICENSE) file for details

## 👥 Authors

- [@holasoymalva](https://github.com/holasoymalva)

## 🙏 Acknowledgments

- [Anthropic](https://www.anthropic.com/) for providing the Claude API
- [Streamlit](https://streamlit.io/) for the interface framework
- The open source community for their contributions

## 📞 Support

If you have any questions or issues:

1. Check [existing issues](https://github.com/holasoymalva/guru-seguros/issues)
2. Open a new issue if needed
3. Contact the development team
