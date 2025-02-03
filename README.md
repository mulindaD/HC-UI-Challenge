# Crypto Buy Widget Challenge

## The Story
HoneyCoin is building a new feature to allow users to easily purchase cryptocurrency using their local currency. We're starting with a widget that lets users buy USDT or USDC through various payment methods. Your challenge is to build a simplified version of this widget's frontend.

## Your Mission
Create an intuitive, multi-step buying experience that guides users from selecting their desired cryptocurrency to completing their purchase. Think of it as building a small but polished part of a larger financial application.

## The User Journey
Imagine a user named Sarah who wants to buy USDT using Kenyan Shillings (KES):
1. She starts by choosing USDT on the Ethereum network
2. She enters her wallet address where she'll receive the tokens
3. She decides how much she wants to spend in KES
4. She sees a clear summary of her transaction before proceeding

## Technical Requirements
Build this experience using:
- Angular 17+ with standalone components
- TypeScript for type safety
- CSS for styling (SCSS is fine too)

Your solution should include:
- A multi-step form that maintains state between steps
- Real-time currency conversion
- Wallet address validation
- A progress indicator showing the user's journey
- Responsive design that works on both desktop and mobile

## Design Reference
In the `/uiMockups` folder, you'll find screenshots of our existing Sell flow widget. While you're building the Buy flow, use these as inspiration for:
- The overall look and feel
- Component styling and layout
- Progress indicator implementation
- Form field designs
- Transaction summary layout

Key design elements to note from the reference:
- Clean, minimal interface with clear hierarchy
- Progress bar showing steps in the flow
- Consistent spacing and typography
- Clear call-to-action buttons
- Information organized in digestible chunks
- Mobile-responsive layout

While the Buy flow will have different steps and fields, the visual language should remain consistent with these reference designs.

## API Integration
You'll need to mock three endpoints that your widget would interact with in production:
- Getting exchange rates
- Validating wallet addresses
- Creating orders

Don't build the actual APIs - instead, create interfaces and mock responses that demonstrate how your frontend would interact with these endpoints.

## Time Box
We respect your time - this challenge is designed to take about 3 hours. It's okay if you don't complete everything; we're more interested in seeing your approach and code quality for what you do finish.

## What We're Looking For
- Clean, well-organized code that others can understand and maintain
- Smart use of TypeScript to prevent bugs
- Reusable components that we could use elsewhere
- Thoughtful error handling that helps users recover from mistakes
- A polished user experience that feels trustworthy

## Bonus Points
- Unit tests for critical features
- Helpful comments explaining complex logic
- Commit messages that tell a story
- A README explaining your technical decisions

Remember: We're not looking for perfection - we're looking for a demonstration of your problem-solving approach and coding style.

Good luck! 🚀