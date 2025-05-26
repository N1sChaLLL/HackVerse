
# HackVerse

HackVerse is an interactive educational website designed to make learning ethical hacking engaging, hands-on, and accessible. By integrating gamification with real-world cybersecurity scenarios, HackVerse transforms traditional learning into an immersive experience. The platform features a variety of challenges—such as brute-force attacks, steganography, packet sniffing, IDOR, and directory traversal—categorized into Beginner, Intermediate, and Advanced levels. Each challenge is presented as a self-contained game, allowing users to safely explore offensive and defensive hacking techniques in a simulated environment. Through personalized dashboards, progress tracking, hints, and a points-based leaderboard system, HackVerse fosters motivation, critical thinking, and practical skill development. Aimed at students and aspiring cybersecurity professionals, HackVerse bridges the gap between theory and practice, preparing users for real-world cyber threats in a fun and educational way.




## Installation

Install my-project with these modules

```bash
from fastapi import FastAPI, Depends, HTTPException, status, Form
from fastapi.middleware.cors import CORSMiddleware
from fastapi.security import OAuth2PasswordBearer, OAuth2PasswordRequestForm
from jose import JWTError, jwt
from passlib.context import CryptContext 
from pydantic import BaseModel, EmailStr, Field, ConfigDict 
from typing import List, Optional, Any, Dict
from datetime import datetime, timedelta
import motor.motor_asyncio 
import os
from bson import ObjectId
from dotenv import load_dotenv 
```
These are the modules that is needed to run this project. FASTAPI is the major module and it is connected with MongoDB
    
## Lessons Learned

We learnt how to use FastAPI for the backend connection. We also learnt that how important it is to know about various cyber threats and attacks. We as a team learnt a lot while building this whole project. 