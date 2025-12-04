# BOMBA NA - SMS Bomber Tool
**Created by Bilyabits**

## Overview
BOMBA NA is an advanced multi-provider SMS bomber tool with 5 different SMS service providers. Designed for educational and testing purposes only.

## Features
- ✅ 5 Working SMS Service Providers
- ✅ Real-time Progress Tracking
- ✅ Detailed Attack Statistics
- ✅ Clean Green/Red/White Theme
- ✅ Async Concurrent Processing
- ✅ Flexible UI Navigation

## Supported Providers
1. **Abenson** - Appliance Store OTP
2. **LBC Connect** - Delivery Service OTP
3. **Excellent Lending** - Loan Provider OTP
4. **WeMove** - Moving Service OTP
5. **Honey Loan** - Loan Service OTP

## Installation
```bash
# Method 1: Install using requirements.txt (Recommended)
pip install -r requirements.txt

# Method 2: Install manually
pip install requests aiohttp

# Method 3: Auto-install on first run
python run.py
```

## Usage
```bash
python run.py
```

### Menu Options
1. **Select Provider** - Choose from 5 SMS providers
2. **About** - View tool information and instructions
3. **Exit** - Exit the application

### Phone Number Format
The tool accepts various Philippine phone number formats:
- `09xxxxxxxxx` (e.g., 09123456789)
- `9xxxxxxxxx` (e.g., 9123456789)
- `+639xxxxxxxxx` (e.g., +639123456789)

### Limit
- Minimum: 1 SMS
- Recommended: 1-300 SMS
- Maximum (safety cap): 500 SMS

## Important Notice
⚠️ **Legal Disclaimer**
- Use this tool responsibly and ethically
- Only use on phone numbers you own or have explicit permission to test
- Misuse may violate local laws and regulations
- The author is NOT responsible for any misuse or illegal activities

## Technical Details
- **Language**: Python 3.7+
- **Async Framework**: asyncio, aiohttp
- **Color Support**: ANSI escape codes
- **OS Support**: Windows, Linux, macOS

## Version
**v1.0.0** - Initial Release

---
**Created by Bilyabits** | For Educational Purposes Only
