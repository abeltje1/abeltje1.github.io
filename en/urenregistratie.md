
# Time tracking with eitje

Just like any other part of eitje, we've tried to keep the feature as simple as possible. However, it's good to have some fundamental knowledge about the inner workings of this feature, because it is of the utmost importance that you don't have any mistakes in your registration. 

**Jump to**
* [The fundamentals](/en/urenregistratie?id=the-fundamentals)
* [Creating timecards](/en/urenregistratie?id=creating-timecards)
* [Approving a timecard](/en/urenregistratie?id=approving-a-timecard)
* [Overview](/en/urenregistratie?id=overview)
* [Leave hours](/en/urenregistratie?id=leave-hours)
* [Improductive hours](/en/urenregistratie?id=improductive-hours)


## The fundamentals

The time registration has several steps for writing and approving the hours. We display these in three different colors:

* **Blue:** This means that the teammember is scheduled, but the hours have not yet been updated for this shift. This time rule will be automatically created for the team member when the shift has started. As long as the timecard is still blue, you can also adjust the shift in the planning.
* **Orange:** After the hours have been written, the timecard will turn orange. This means that the hours have been written, but the hours have yet to be approved by someone with the **Approve hours** role . You can also no longer take this person off the schedule. As long as the hours have not yet been processed, they won't be included in the export.
* **Green:** If the hours have been approved by a manager, the timecard will turn green. This means that the hours have been approved and that they can be exported to the payroll. If a mistake has been made, you can of course still adjust the hours.

In addition, there are three more colors to indicate a special action:

* **Purple:** Is used for timecards which indicate leave is taken. Leave can also be written for a team member depending on the contract type. These hours will be shown in purple and will therefore be deducted from the leave balance.
* **Red:** A red timecard shows unproductive hours like **Sick & Special leave**. You only need to use this if you also use the leave and / or plus / minus functionality. This way you ensure that this registration is correct.
* **White:** When timecards have been exported to one of our partners, the hours lines will be colored white. 



---

## Creating timecards

In short, there are two ways to creata a timecard:

* The timecards are automatically created for shifts at the start time of the shift.
* Through **Hours > Overview** you can manually add hours by creating a new timecard by clicking **Add**.

> If the timecard is created from a shift, it will always use the start and end times of the shift. In addition, the break and meal allowance are also included in the planning.


---

## Approving a timecard

Approval of a timecard can only be done by team members with the role: **Approve hours** . Team members who have this role simply need to check the hours and approve them. They can do this via the app or through the web platform. In this video we look at the possibility to approve several timecards with a single click.

<video controls
       muted 
       src="/assets/snelAccorderenV2.mov"
       width="683"
       height="384">
</video>

---

## Overview

It is also possible to approve timecards in the overview. You simply do this by clicking on a timecard and then hit **Approve**. 

> If you scroll down in the pop-up, you will see audits of who and what has changed in the timecard.


<video controls
       muted 
       src="/assets/weekOverzichtV2.mov"
       width="683"
       height="384">
</video>

---

## Leave hours

All timecards with the type: **Leave** will be colored in purple and will be taken out of the leave balance. We advise you to read up on our extensive manual for the leave registration [over here](/en/verlof).

---

## Improductive hours

If a team member cannot work because being of illness or special leave, you can register this with the type: Improductive. 

> You will only need to use this type if you keep track of the overtime balance. This way you ensure that teammember won't end up with a negative leave balance.

* **Special leave:** You can change the type of the timecard if there are special circumstances for which you give a teammember time off. By writing special leave, eitje will counts the timecard as if it these hours are worked, but it will not have a negative effect on their overtime balance. 
* **Sick:**  In case of illness of team members, you can change the timecard type to: Sick. As with special leave, this ensures that the missed hours do not affect the team member's balances.

<video controls
       muted 
       src="/assets/improductief.mov"
       width="683"
       height="384">
</video>

---