# AI Code Generator

यह एक ओपन-सोर्स AI टूल है जो **React, HTML/CSS, JavaScript** में कोड जेनरेट करता है।

## आवश्यकताएँ
- Python 3.8+
- Node.js
- CUDA सपोर्टेड GPU (वैकल्पिक)

## चलाने के लिए निर्देश
1. Backend चलाएं:
   ```bash
   cd backend/
   pip install fastapi uvicorn transformers torch
   python -m uvicorn app:app --reload