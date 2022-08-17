# Auto Assign Customer To Discount Group (Admin)

## Turning on functionality

1. Choose the ![Tell me what you want to do](media/TellMe.png) icon. Enter **Sales & Receivables Setup**. Choose the related link.
2. In "Auto Assigned Customer Discount Group" Group find **Auto Assigned Cust. Disc. Group** and turn it on.

> [!Note]
>
> Value of **Period of Validity** must be greater or equal **1D**.
>
> Value of **Turnover Period** bust be less or equal **-1D**.

## Set the requirement for assign to discount group.

1. Choose the ![Tell me what you want to do](media/TellMe.png) icon. Enter **Requirements Auto Ass. Disc. Group**. Choose the related link.
2. Select a Record or create a new one.
3. **Code** field represents **Customer Disc. Groups**.
4. **Required** field is used for set requirement that must be met for assign to that group. All requirements must have different value.
5. After changes find action **Release** (Actions -> Release -> Release) and use it.

> [!Note]
>
> User can make changes when **Status** in "Auto Assigned Customer Discount Group" in **Sales & Receivables Setup** is *Open*. When **Status** is *Released* use action **Open** (Actions -> Release -> Open) in **Requirements Auto Ass. Disc. Group**. 

## Auto assign Customer to discount group
1. Choose the ![Tell me what you want to do](media/TellMe.png) icon. Enter **Customers**. Choose the related link.
2. Choose **Customer** from the list and open **Customer Card**.
3. When functionality is turned on it should not be possible to manually manipulate with **Customer Disc. Group**.
4. You can use action to auto assign this Customer to discount group. Find action **Auto Assign To Disc. Group** (Actions -> Auto Assign To Disc. Group) and run it.
5. See Customer is assigned to discount group and fields **Auto Assigned Disc. Expiration Date**, **Auto Assigned Disc. Expiration Date**, **Last Auto Assigned Changed By** and **Last Auto Assigned Changed Date** have been changed.

> [!Note]
>
> New created Customer will be auto assigned to **Customer Disc. Group**.

## Auto assign all Customers to discount group
1. Choose the ![Tell me what you want to do](media/TellMe.png) icon. Enter **Requirements Auto Ass. Disc. Group**. Choose the related link.
2. Find action **Auto Assign All Cust. To Disc. Group Report** and rut it.
3. Request page **Auto Assign All Customers To Discount Groups** show up. In this page is only one field **Auto. Assign All Cust. To Disc. Group**. If it is *turned off* Customers with invalid assigned will be assigned.
If it is *turned on* all Customers will be assigned.

> [!Note]
>
> This action is available when **functionality** is *turned on* and **status** is *released*.

## Create new Sales Document
1. Choose the ![Tell me what you want to do](media/TellMe.png) icon. Enter **Sales Order**. Choose the related link.
2. Set Customer in **Customer Name** field. When Customer has invalid assigned this page show error. When Customer has valid assigned, all should work correctly.

> [!Note]
>
> When sales document is going to be created from action in **Customer Card** page. Error will show up when Customer has invalid assigned.
>
> All old document with customer with invalid assigned will work correctly.

## History of auto assign to discount group
### Search history page in tell me what you want to do
1. Choose the ![Tell me what you want to do](media/TellMe.png) icon. Enter **Auto Assing To Cust. Disc. Gr. Hist.**. Choose the related link.
2. Auto Assign To Cust. Disc. Gr. Hist. page show up.
### From Customer Card page.
1. Choose the ![Tell me what you want to do](media/TellMe.png) icon. Enter **Customers**. Choose the related link.
2. Choose **Customer** from the list and open **Customer Card**.
3. Find action **History Auto Ass. To Disc. Gr.** (Actions -> History Auto Ass. To Disc. Gr.) and run it.
4. Auto Assign To Cust. Disc. Gr. Hist. page show up. List is filtered by *Customer No.*.