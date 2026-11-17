<img width="162" height="43" alt="image" src="https://github.com/user-attachments/assets/6620bf4f-78f0-418d-911f-263136dcefea" />

# Microsoft Copilot Studio - AI Agent Creation and Deployment

This tutorial outlines the step-by-step process of creating, configuring, testing, and publishing an AI-powered agent using Microsoft Copilot Studio.

## Project Summary

This project demonstrates the implementation of an AI agent using Microsoft Copilot Studio, a low-code platform within the Microsoft Power Platform ecosystem.

The objective is to create an agent capable of responding to user inquiries, utilizing configured instructions and knowledge sources, and assisting with business-related tasks.

The project covers the complete agent development lifecycle, including initial creation, configuration, testing, troubleshooting, and deployment.

## Environments and Technologies Used

- Microsoft Copilot Studio
- Microsoft Power Platform
- Microsoft 365
- Microsoft Entra ID
- Microsoft Edge
- Microsoft Dataverse (environment-dependent)

## Operating Systems Used

- Windows 11

## Programming Languages Used

- No traditional programming languages required
- Natural-language instructions
- Low-code configuration

## Agent Development Stages

- Accessing Microsoft Copilot Studio
- Creating a New Agent
- Configuring Agent Details and Instructions
- Adding Knowledge Sources
- Configuring Agent Capabilities
- Testing the Agent
- Troubleshooting and Refinement
- Publishing the Agent
- Configuring Deployment Channels
- Final Validation

# Implementation Walkthrough

## Step 1: Accessing Microsoft Copilot Studio

1. Open Microsoft Edge and navigate to https://copilotstudio.microsoft.com.
2. Sign in using a Microsoft work or school account with access to Copilot Studio.
3. Locate the environment selector.
4. Select the appropriate Power Platform environment.
5. Verify that the Copilot Studio interface loads successfully.

The selected environment determines where the agent and its associated resources will be managed.

**Expected Result:** Microsoft Copilot Studio is accessible, and the correct environment is selected.

![Copilot Studio Home Page](images/01-copilot-studio-home.png)

## Step 2: Creating a New Agent

1. Navigate to the **Agents** section.
2. Select the option to create a new agent.
3. Choose the available agent creation method.
4. If prompted, describe the purpose and intended functionality of the agent.
5. Complete the creation process.
6. Wait for Copilot Studio to initialize the agent.

**Expected Result:** A new agent is created and available for configuration.

![Creating a New Agent](images/02-create-agent.png)

## Step 3: Configuring Agent Details and Instructions

1. Open the newly created agent.
2. Navigate to the agent's overview or details section.
3. Enter an appropriate name for the agent.
4. Provide a description explaining its intended purpose.
5. Locate the **Instructions** configuration area.
6. Enter instructions defining the agent's responsibilities and expected behavior.
7. Establish any necessary response formatting or operational restrictions.
8. Save the configuration.

Agent instructions define how the AI should respond to users and what responsibilities it should prioritize.

**Expected Result:** The agent's identity and instructions are successfully configured.

![Agent Configuration](images/03-agent-configuration.png)

## Step 4: Adding Knowledge Sources

1. Navigate to the agent's **Knowledge** section.
2. Select **Add knowledge**.
3. Review the available knowledge source options.
4. Select an appropriate source, such as a website, uploaded document, or SharePoint location.
5. Enter the required information or upload the selected file.
6. Complete the configuration process.
7. Verify that the knowledge source appears in the agent's configuration.

Knowledge sources allow the agent to reference designated information when generating responses.

**Expected Result:** The selected knowledge source is added and available once processing is complete.

![Knowledge Source Configuration](images/04-knowledge-sources.png)

## Step 5: Configuring Agent Capabilities

1. Open the agent's configuration sections.
2. Review the available generative AI settings and capabilities.
3. Determine whether additional tools, actions, or integrations are required.
4. Configure the capabilities appropriate for the agent's intended functionality.
5. Review authentication and access settings where applicable.
6. Save any configuration changes.

Additional capabilities may include connectors, tools, or Power Automate flows that allow the agent to perform tasks beyond answering questions.

**Expected Result:** The required agent capabilities are configured successfully.

![Agent Capabilities](images/05-agent-capabilities.png)

## Step 6: Testing the Agent

1. Open the agent's test chat panel.
2. Enter a question related to the agent's intended purpose.
3. Review the generated response.
4. Verify that the response follows the configured instructions.
5. Submit additional questions to test different scenarios.
6. Test knowledge retrieval if a knowledge source was configured.
7. Evaluate how the agent handles unsupported or unrelated questions.

Testing is necessary to verify that the agent behaves as expected before deployment.

**Expected Result:** The agent generates appropriate responses and follows its configured instructions.

![Testing the Agent](images/06-agent-testing.png)

## Step 7: Troubleshooting and Refining the Agent

1. Review any inaccurate or incomplete responses identified during testing.
2. Return to the agent's instructions or relevant configuration section.
3. Modify the configuration to address the identified issue.
4. Verify that the necessary knowledge sources are correctly configured.
5. Save the changes.
6. Return to the test panel.
7. Repeat the original test to evaluate whether the issue has been resolved.

This process allows the agent's behavior to be refined through iterative testing and configuration adjustments.

**Expected Result:** The agent demonstrates improved accuracy and consistency during testing.

![Agent Troubleshooting](images/07-agent-troubleshooting.png)

## Step 8: Publishing the Agent

1. Open the agent in Microsoft Copilot Studio.
2. Locate the **Publish** option.
3. Review any publishing requirements or validation messages.
4. Select **Publish**.
5. Confirm the publishing action if prompted.
6. Wait for the publishing process to complete.
7. Verify that Copilot Studio reports a successful publication.

Publishing prepares the configured version of the agent for use through supported deployment channels.

**Expected Result:** The agent is successfully published.

![Publishing the Agent](images/08-agent-publishing.png)

## Step 9: Configuring Deployment Channels

1. Navigate to the agent's **Channels** section.
2. Review the available deployment options.
3. Select the appropriate channel, such as Microsoft Teams if supported.
4. Complete the required channel configuration.
5. Review authentication and sharing requirements.
6. Save the configuration.
7. Complete any additional deployment or publishing steps required by the channel.

Deployment channels determine where users can access and interact with the published agent.

**Expected Result:** The selected deployment channel is configured successfully.

![Deployment Configuration](images/09-deployment-channels.png)

## Step 10: Final Agent Validation

1. Access the published agent through its configured deployment channel.
2. Start a new conversation.
3. Submit a question related to the agent's purpose.
4. Verify that the agent responds appropriately.
5. Test any configured knowledge sources or additional capabilities.
6. Confirm that the agent follows its configured instructions.
7. Document the results of the final test.

Final validation confirms that the agent has successfully progressed through the development, testing, and deployment process.

**Expected Result:** The agent is accessible through its configured channel and functions as intended.

![Final Agent Demonstration](images/10-final-validation.png)

# Project Outcome

This project demonstrates the process of developing an AI-powered conversational agent using Microsoft Copilot Studio.

The implementation covers:

- AI agent creation and configuration
- Natural-language instruction development
- Knowledge source integration
- Agent capability configuration
- Functional testing and troubleshooting
- Cloud-based publishing
- Deployment channel configuration
- Final implementation validation

The project demonstrates practical experience with Microsoft Power Platform technologies and low-code AI application development.

# Conclusion

Microsoft Copilot Studio provides a low-code environment for developing AI agents that can assist users, retrieve information from configured knowledge sources, and support organizational workflows.

This project demonstrates the foundational skills required to configure, test, and deploy an AI-powered agent using Microsoft cloud technologies.
