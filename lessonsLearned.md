# Lessons Learned
Part of writing good requirements is knowing your audience, so I'm just going to let you know about some of my opinions up front.

## 1. Don't kill me with bullets
Having a long unordered list of requirement statements is cruel and unusual punishment.  If it is important enough to write down, then it is important enough to assign a unique identifier.  Not only does this provide a short-hand to the team, but allows for traceablity for scoping and testing conversations.

## 2. Source your requirements
Requirements do not come out of thin air. Your stakeholders may disagree over the requirements.  Business context may render some requirements obsolete.  Reference the person, policy or best practice.  This will help you return to the source with clarifying questions or when the validity is questioned.

## 3. Use Appropriate Language
Requirements are non-negotiable and uses words like “shall,” “must,” or “will.” This is a pass/fail situation.  If you are using passive words like “should” or “may”, then it sounds a nice-to-have feature or option. 

## 4. Use Categories that make sense for your audience
Many of your future clients will think of requirements based on a business process or a role, so group your requirements in that fashion.  In this excercise, you should demonstrate that you are capturing the full spectrum on business through system requirements.  

Here are some sample requirements statements

- **Business**: The business objective that the system needs to satisfy.
  - B.1 The system must limit orders based on staff capacity, so that the delivery Service Level Agreement of within 10 minutes of promised delivery is not placed in jeopardy. (Pointy Hair Boss)
- **User**: The actions that a user takes within the system
  - U.1 The user must associate their account with payment method (e.g., Falcon Dollars or Credit Card) (Hungry Student 1).
- **Functional**: The functions should the system perform
  - F.1 The system must present an anticipated delivery time prior to allowing the user to confirm the order (Hangry Student 2).
- **Non-Functional**: The characteristics that the system should have.
  - N.1 The system must render pages in less than 10 seconds after any user action or application event. (UX Expert Lady)
- **System**: Specifications about how the system should be built.
  - S.1 The system must use Messiah University Single Sign On (SSO) solution for any accounts with a messiah.edu domain. (Policy IT01.02)
