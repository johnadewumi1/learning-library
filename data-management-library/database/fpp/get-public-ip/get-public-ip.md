# Get the public IP of the FPP Server

It might sound obvious, but **please, don't use the values provided in the example images**, get the values that are proper to your reservation!

Estimated lab time: 5 minutes

## Objectives 
In this lab, you will:
- Access the OCI Console
- Verify your Region and Compartment
- Access your public IP

### Prerequisites
- An assigned Oracle LiveLabs Cloud account
- An assigned compartment

## **Step 1:** Access the OCI Console
1. Access the OCI Console using the **User Name**, **Initial Password** and **Login URL** that you received with your Livelabs Reservation confirmation.

    ![](./images/00-reservation.png)

2. Change the password as required.

## **Step 2:** Verify your Region and Compartment
1. Make sure that the **Region** (top-right corner) corresponds to the one you received in the reservation confirmation.

2. Navigate from the Hamburger Menu (top-left corner) to **Oracle Database** -> **Bare Metal, VM, and Exadata**.
![](./images/bare-metal.png)

3. **Important**: in the left menu, under **List Scope**, verify that you select the same compartment that you received in the reservation confirmation.
    ![](./images/02-select-compartment.png)

## **Step 3:** Get the Public IP of the FPP Server
1. Click on the DB System name **fpps-cluster-wxyz** (wxyz is your reservation number: the number that compose also your Compartment name, e.g. LLwxyz-COMPARTMENT).

    The DB System Details page appears:
    ![](./images/03-dbsystem-status.png)

2. Scroll down, at the end of the left pane click **Nodes(1)**, then note down the Public IP Address.
    ![](./images/04-nodes-public-ip.png)

You may now [proceed to the next lab](#next) and connect to the server.

## Acknowledgements

- **Author** - Ludovico Caldara
- **Contributors** - Kamryn Vinson
- **Last Updated By/Date** -  Kamryn Vinson, April 2021