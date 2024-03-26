# How-To: Automatic Recurring Transfers (ARTs) and Irrevocable Transfers

(Formerly known as Forward Transfers and Standing Orders)

ARTs are established to automatically transfer a specified quantity and vintage of RECs to the recipient when generation is uploaded for the generator. ARTS can be external (to another M-RETS Organization) or internal (to an internal active account). Irrevocable Transfers are ARTs that can not be edited after they are created and accepted by the recipient. The M-RETS Administrator has the sole ability to remove the irrevocable flag if selected. 

Select the 'Transactions' dashboard. You will now see three tabs on this page: Pending, History, and Recurring. Select 'Recurring'.

To add an ART:
-   Select 'Add Recurring Transfer'

![](https://github.com/mrets/photos/blob/master/automatic_recurring_transfers1b.png?raw=true)

## Select Generator

- Select the generator that you wish to associate an ART with. Once a generator is selected, you will see fuel(s) related to the generator.

![](https://github.com/mrets/photos/blob/master/automatic_recurring_transfers2b.png?raw=true)


<br>

## Select Vintage Dates

If a specific vintage range is selected generation within the specified vintage range will be transferred at upload, if open-ended is selected certificates will be transferred from the start vintage specified. 

<ul>
  <li>Select your certificate vintage start date and end date that you wish to be included in the ART. Your transfer will be initiated every month during the calendar timeframe selected when generation is uploaded.</li>
  <li>If your project is a multi-fuel generator, select a fuel type for your transfer. For multi-fuel generators, the automatic recurring transfer will only pertain to one fuel type.</li>
  </ul>

![](https://github.com/mrets/photos/blob/master/automatic_recurring_transfers3b.png?raw=true)


<br>

## Select Transfer Option

-   ARTs can have three potential transfer options; internal, external, or export (out of the M-RETS platform).

![](https://github.com/mrets/photos/blob/master/automatic_recurring_transfers5b.png?raw=true)


<br>

### Internal Transfer to Active Account(s)

Select your account(s) from the menu. If you select multiple, you will see them populate at the bottom of the screen.

<ul>
  <li>Enter a percentage split based on your accounts. **NOTE**: The total must add to 100%.</li>
  <li>You can drag the different accounts to reprioritize them. In the event the quantity does not divide evenly the majority will be allocated to the first listed account.</li>
  <li>Select 'Review'</li>
  </ul>

![](https://github.com/mrets/photos/blob/master/automatic_recurring_transfers20?raw=true)

<br>

### External Transfers to another M-RETS Organizations

External transfers can only be associated with one receiving organization. Certificates can be allocated by either a percentage or quantity. 

- Select the organization to which you would like to transfer, all M-RETS Organizations will appear here.

![](https://github.com/mrets/photos/blob/master/automatic_recurring_transfers6b.png?raw=true)

- Input either a max value as a quantity or percentage of certificates, in this example the irrevocable flag has been checked. Select 'Review'. 

![](https://github.com/mrets/photos/blob/master/automatic_recurring_transfers21.png?raw=true)

**NOTE**: Recipient organizations are required to intially accept an ART before they are enabled. 

<br>

### Out of the M-RETS Platform (export)

For ARTs as an export, you will either input a percentage or max value quantity. 

-   Select the tracking system to which you intend to export from the dropdown menu.
-   Enter the recipient Account Holder as it is registered in the receiving tracking system.
-   Select 'Next' and input the max value quantity or percentage.
-   Select 'Review'

![](https://github.com/mrets/photos/blob/master/automatic_recurring_transfers9b.png?raw=true)

For all ARTS the System will ask you to review the information before creating the transfer, after review select 'Add' on step 5. 

How to: [Withdrawing/Accepting/Rejecting Transfers](https://mrets.github.io/Help/transactions_withdrawing_accepting_rejecting_transfers)
