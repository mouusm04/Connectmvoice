site_name: MkLorum
# Chapter 3 Feature

What you will learn:

- [Call Center](#call-center)
- [Conference](#conference)
- [Ring Groups](#ring-groups)
- [Distribution List](#distribution-list)
- [Speed Dial](#speed-dial)
- [Greeting Manager](#greeting-manager)




## Call Center

ConnectMeVoice offers a range of incoming Call Center capabilities as an add-on. When you log in to the End User Portal, you will notice a Call Center option on the left side bar if you have purchased the Call Center service.

The following components are included in the call center:

- Agents
- Queue
- Tiers

### Agents
An Agent represents a person. The Agent can then be assigned one or more phones or phone registrations. This allows you to have an Agent receive more than one call, or to receive calls on different devices.

To view the list of agents, navigate to **Feature > Call Center > Agents**.

![Image](../image/Agents_List.jpg)

#### Add a new agents

1. Click the **+Add New** button on the top right corner. A new window will appear.

    ![Image](../image/Agents_List-addnew.jpg)

2. Enter the required information in the following fields:

    - Set agent’s name.
    - Add Outbound Caller Id Number.
    - Manage and set time for:
        - Call Timeout
        - Max No Answer (Number of Times 0=disabled)
        - Wrap Up Time (Seconds 0=disabled)
        - Reject Delay Time (Seconds 0=disabled)
        - Busy Delay Time (Seconds)
        - No Answer Delay Time (Seconds 0=disabled)
    - List VoIP Phone, Extension Number, or Phone Number of agent.

3. Click **Save**
 
#### Edit or Delete an existing Agent

You may also modify or delete a agent by selecting it and clicking the edit or delete icon next to it.


### Queues

A queue represents a calling strategy. For example, you may have all the agents ring at the same time (ring-all) or have them ring sequentially or in a round robin. When a call comes in, you have the option of announcing the caller's location, allowing an escape to voicemail, or displaying specific information on your phone. Inside the Call Center Queue, call recording must be enabled. Any call routed to the Call Center will not be recorded if call recording is disabled in the Queue.

To view the list of Queues, navigate to **Feature > Call Center > Queues**.
    ![Image](../image/call_centre_queues.jpg)

#### Add a new Queues

1. Click the **+Add New** button on the top left corner of the window. A new window will appear.

    ![Image](../image/add_new_queues.jpg)    

2. Enter the required information in the following fields:

    - Input name, details, keys, and strategies. 
    - Add Exit Keys (numbers only)
    - Choose option to Skip Route if all agents are busy. Include max wait time with no agent reached.
    - Tick option to record, play, or announce caller position and for how long.
    - Decide on a time-based score, whether you use Queueing or System.
    - Tick box if you wish to announce call and choose if you want Prefix Queue Name To Caller Id Name or Prefix Caller Id Name.
    - Decide if you wish for an Abandoned Resume Allowed and Discard Abandon After.
    - Display status
    - Check between Tier Rules Apply, Tier Rule Wait Seconds, Tier Rule Wait Multiply Level, or. Tier Rule No Agent No Wait.


3. Click **Save**    

#### Edit or Delete an existing Queues

You may also modify or delete a Queues by selecting it and clicking the edit or delete icon next to it.


### Tiers

A Tier defines how Agents are connected to Queues. For example, you may have Agents Mary, Sue and John tied to the Sales Queue. In addition, the Tier allows you to prioritize some Agents over others in a ring-all group. For instance, you want to call Mary and Sue first, then have John call after 30 seconds of the phone ringing.

To view the list of Tier details:

1. Navigate to **Feature > Call Center > Tiers**.

2. Select a Queue from the dropdown list. A new window will appear.

    ![Image](../image/call_centre_tier.jpg)

#### Add a new Tiers    

1. Click the **+Add New** button on the top left corner of the window. A new window will appear.

    ![Image](../image/add_new_tier.jpg)    

2. Enter the required information in the fields provided.

3. Click **Save**  

## Conference 

### Conference Bridge
ConnectMeVoice offers an optional meet-me conference bridge. If you have purchased this feature 
you may access the bridge from a VoIP Phone with a direct dial extension, and from an outside 
line using a phone number. The bridge comes with call recording, access code protection and an 
optional caller announce.

If you have a conference bridge set up on your account, any user on the account can dial in internally 
to the conference call using the extension assigned to that bridge (for example ext. 3000) and 
use the member pin. When you invite outside callers to a conference call, have them dial into the 
Conference Bridge phone number, and give them the member pin. As each member joins, they 
will not be able to hear each other until the moderator joins with their moderator pin. If you want 
everyone to hear each other as they join in to the call, then the moderator pin should be the same 
as the member pin.

If you have more than one Conference Bridge, then you will have an extension/phone number for 
each; and each bridge will have its own member pin and moderator pin.

![Image](../image/conference_bridge.jpg) 

## Ring Groups

As an Administrator, you can setup a group of your VoIP phone extensions to all ring at the same  time. You can also have a group mixed with VoIP Phones and outside phone numbers. The group can also be named for easy reference (e.g. "Customer Service"). After the Ring Group has been created, you can select the group in call routing.

To view the list of Queues, navigate to **Feature > Ring Groups**
    ![Image](../image/Ring_Group.jpg)

#### Create a new Ring Groups     

1. Click the **+Add New** button on the top right corner. A new popup will appear.

2. Assign a new name to the group.

3. Click **Save**.

**Note: There are no limits on how many Ring Groups that can be created, and they can be used as needed.**

#### Add members to a Ring Groups 

1. To add a member, Click the **+ Add Member** icon next to each group. A new popup will appear.

    ![Image](../image/add_member.jpg)

2. Choose phone type and place details on the box provided. For VoIP phones, specify a caller ID prefix to the members of a Ring Group.


#### Quick Add

The Quick Add feature allows the full listing of a group and member. This is ideal for administrators who already have a list in mind.

To quickly add a new member:

1. Click the **+ Quick Add** button on the top right corner. A new window will appear.

    ![Image](../image/Quick_add.jpg)

2. Assign a name to the Ring Group and click **Save**.
3. Choose your Ring Group from the dropdown list.    
4. Add members to group by moving them to the right with the arrows, click **Save**.

## Distribution List

You can create a distribution list, which is simply a collection of extensions. This is used to send a voicemail blast to all of those extensions. Please dial *99, press 2, and follow the instructions.

To view the Distribution List, navigate to **Feature > Distribution List**
    ![Image](../image/Distribution_list.jpg)

#### Add a new member to distribution list

To add a member to distribution list

1. Click the **Add Member** icon next to the distribution list row. A new window will appears.
    ![Image](../image/add_member_DL.jpg)

2. To start a new search, use the extension number or the first or last name of a member. Click on the **Search** button.
A new window with the search results will appear.
    ![Image](../image/searchresult_member.jpg)

3. Select the required member and click the **Add Selected Member** button. The new member will be added to the distribution list.

#### Rename or Delete a Distribution List

You may also rename or delete a distribution list by selecting it and clicking the rename or delete icon next to it.

## Speed Dial

Speed dial allows you to sync to the directory buttons on the phone for easier and faster contacting.

To view your speed dial, navigate to **Feature > Speed Dial**. You can view your speed dial by **Extensions** or **Corporate** numbers.
    ![Image](../image/speed_dial.jpg)

## Greeting Manager

"Greetings" are what the caller hears when they dial your service. You can either record your greetings over the phone or use the End User Portal to upload one. Some greetings, such as the main (auto-attendant) greeting, are setup by the administrator; others are setup by each individual user.

To view the list of greetings, navigate to **Feature > Greetings**
    ![Image](../image/Greetings.jpg)

#### Add mailbox greetings

The Greeting Manager allows users to upload new or updated greeting files to your extension. Additionally, you can preview the greeting by clicking the play sound button.

To add a new greeting:

1. Click the **+Add New** button. A new Add Mailbox Greetings pop-up will appear.
    ![Image](../image/add_greetings.jpg)

2. Select the appropriate greeting type from the drop-down menu, browse for and select your file.
3. Click **Save**.

**NOTE: Only files in the.wav or.mp3 format can be used to upload greetings to the End User Portal.**

#### Download or Delete a Greeting

You may also download or delete a greeting by selecting it and clicking the download or delete icon next to it.