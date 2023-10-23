# FAQs

## Does MAAD-AF really stand for M365 & Azure AD Attack Framework?
A: Yes ;) 

## Why is MAAD-AF not built using Microsoft Graph?
A: While Microsoft Graph is the future of interacting with most Microsoft services and is very useful, many needed functionalities are not yet available in certain services of Microsofty cloud. MAAD-AF leverages Graph in certain techniques where it makes sense and will continue migrating existing MAAD-AF modules to Graph as it makes sense. 

## What credentials do I need to perform testing with MAAD-AF?
A: You can use any Entra ID credential to test with MAAD-AF. It is encouraged to test with different credntials of varying privilges & access. This allows to emulate how different compromised identities would look like in your environment. In general - the higher the privileges, the more techniques you can execute at once, inturn broader testing scope. 

## How can I add my own custom techniques to MAAD-AF attack library?
A: Write your attack technique in PowerShell and include the file in `/Library`. Add an execution option in `/Library/MAAD_Attack_Arsenal.ps1`

## Is MAAD-AF free?
A: Yes, MAAD-AF is an open-source tool and will always remain free.

## Why test with compromised credentials? 
A: Testing with "compromised" credentials allows organizations to emulate a real breach or scenario of credential compromise. Running MAAD-AF with a "compromised" credential allows you to evaluate what's possible for an attacker if organization credentials were compromised and what visibility/response capabilities (& their efficacy) does the organization have to detect and stop these attacks in time. 

## Should I worry about my infrastructure while testing with MAAD-AF?
A: Yes, you should always be cautious when emulating attacks in your environment. The interactive workflow of MAAD-AF allows users to have full control of techniques being executed and resources being targeted. MAAD-AF attempts to provide detailed of information of each module along with MITRE technique association so users can form an informed decision about a modules actions. MAAD-AF also allows to revert actions executed by most modules to minimize the impact to infrastructure. But even with all of these, be very cautious and smart with security testing your environment. 