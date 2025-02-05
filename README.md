

# Getting Started with Amplify CLI

Step 0: Install Amplify CLI using `npm install -g @aws-amplify/cli` or `curl -sL https://aws-amplify.github.io/amplify-cli/install | bash && $SHELL`

Step 1: git clone https://github.com/kaustavghosh06/sampleamplifyapp.git && cd sampleamplifyapp

Step 2: Run `amplify configure` to setup a default AWS Profile in your ~/.aws directory tied to your AWS account

Step 3: Run `amplify init` - choose defalts and select the  profile setup above to initialize your amplify project in your AWS account

Step 4: Run `amplify push --yes` to provision the resources in the project to your AWS account via CloudFormation 

Helpful resources:
- Amplify documentation: https://docs.amplify.aws
- Amplify CLI documentation: https://docs.amplify.aws/cli
- More details on this folder & generated files: https://docs.amplify.aws/cli/reference/files
- Join Amplify's community: https://amplify.aws/community/
