# Auto-create-packages-for-Sales-Orders

Creates Package right after an order is created.

# Steps
# 1. Create Custom function

Settings > Automations > Custom Functions > New Custom Function 

Module: Invoice

Copy and paste the script Auto-create-packages-for-Sales-Orders.

Create connection for Zoho Inventory - zilink

# 2. Create workflow

Settings > Automations > Workflow Rules > New Workflow Rule

Module : Sales Order

Workflow Type : Event Based

When an Invoice is: Created

Choose the appropriate custom function in the Action.

Save the workflow. On each SO creation workflow automatically creates the package.
