                                                                         
  # WOD Recommender                                                             
                                                                                
  A Streamlit-based web application that generates personalized Workout of the Day (WOD) recommendations using Google's Gemini AI.                           
                                                                                
  ## Features                                                                   
                                                                                
  - **Smart Workout Generation**: AI-powered workout recommendations tailored to
   your needs                                                                   
  - **Injury Awareness**: Specify body parts with pain or disabilities to receive safe exercise suggestions                                             
  - **Target Muscle Selection**: Choose which body parts you want to focus on   
  - **Multiple Training Modes**: Support for hypertrophy, strength, and interval training styles                                                              
                                                                                
  ## Requirements                                                               
                                                                                
  - Python 3.x                                                                  
  - Streamlit                                                                   
  - Google Generative AI (Gemini)                                               
  - Pillow                                                                      
  - Requests                                                                    
                                                                                
  ## Installation                                                               
                                                                                
  1. Clone the repository:                                                      
     ```bash                                                                    
     git clone https://github.com/ylemnox/WOD.git                               
     cd WOD                                                                     
                                                                                
  2. Install dependencies:                                                      
  ```bash
  pip install -r requirements.txt
  ```                                      
  3. Configure your Gemini API key in `WOD_recommender.py`:                       
  ```python
  genai.configure(api_key='YOUR_API_KEY')
  ```                                    
                                                                                
  Usage                                                                         
                                                                                
  Run the Streamlit application:  
  ```bash
  streamlit run WOD_recommender.py
  ```                                              
                                                                                
  Then open your browser to the provided local URL (typically http://localhost:8501).                                                       
                                                                                
  How It Works                                                                  
                                                                                
  1. Select Pain/Disabled Areas: Mark any body parts experiencing pain or injury (triceps, biceps, chest, back, wrist, elbow, knee, leg, abs, shoulder)       
  2. Choose Target Areas: Select the muscle groups you want to train            
  3. Pick Workout Type: Choose between hypertrophy, strength, or interval training                                                                      
  4. Get Recommendations: Click "Recommend" to receive 4-5 AI-generated exercises with sets and reps                                                  
                                                                                
  Supported Body Parts                                                          
  Pain/Disability Areas: Triceps, Biceps, Chest, Back, Wrist, Elbow, Knee, Leg, Abs, Shoulder                                                               
  Target Areas: Triceps, Biceps, Chest, Back, Leg, Abs, Shoulder                
  Workout Types                                                                                                                                              
  - Hypertrophy: Focus on muscle growth with moderate weight and higher reps    
  - Strength: Emphasis on building raw strength with heavier loads              
  - Interval: High-intensity interval-style training                            
                                                                                                                
                                                                                
  Credits                                                                       
                                                                                
  Created by @road_to_1000lb                                                    
                                                                                
  Powered by Google Gemini                                                      
                                                                                
  ---       
