# MicroWealth AI

**Project Overview and Purpose**
MicroWealth AI is an educational investing assistant that helps first-time investors learn how to build balanced, low-cost ETF portfolios. The goal is to make investing approachable and understandable rather than intimidating. Users answer a few simple questions about their investment goals, time horizon, and risk tolerance. The AI then creates a sample ETF portfolio, explains the reasoning behind it, and displays it in clear, friendly language. The project is meant to teach the principles of diversification and risk management without giving financial advice.

**Instructions for Viewing and Running the Project**

1. Download or clone this repository to your computer.
2. Open the `index.html` file in any web browser.
3. Fill in the short form with your investment goal, time horizon (in years), risk tolerance (low, medium, or high), and monthly contribution.
4. Click **Generate Portfolio**. The app will display a suggested ETF portfolio, a short rationale, and a reminder that it is an educational tool only.
5. You can adjust your inputs and regenerate new portfolios to see how risk level and time horizon change the output.

**AI Component**
**What the AI does:**
MicroWealth AI uses Google’s Gemini 1.5 Flash model to create and explain ETF portfolios based on user inputs. When the form is submitted, Gemini takes the user’s information and returns a structured JSON response that includes the portfolio name, the ETF symbols and weights, a rationale for the allocation, a rebalancing frequency, and a disclaimer.

**Why this AI was chosen:**
Gemini 1.5 Flash was selected because it provides strong reasoning, fast responses, and clear language generation. These strengths make it ideal for financial education, where transparency and clarity matter more than speed trading or predictions. It can also generate structured outputs (JSON) that are easy to format into readable web content.

**How it improves or supports the product’s goal:**
Gemini transforms user inputs into meaningful educational insight, turning abstract investing concepts into personalized examples. Instead of just listing funds, it explains why each portfolio makes sense for that user’s risk tolerance and time horizon. This builds confidence and understanding — the core goal of MicroWealth AI. The AI’s reasoning also reinforces financial literacy by showing users how balanced investing works in practice while maintaining ethical boundaries (no personalized investment advice).


