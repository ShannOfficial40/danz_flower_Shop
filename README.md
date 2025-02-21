<%@ Master Language="C#" AutoEventWireup="true" CodeBehind="danz_flower_shop.master.cs" Inherits="danzFlowerShop.danz_flower_shop" %>
<!DOCTYPE html>
<%--This is the main web form that each web page will inherite--%>
<html>
<head runat="server">
    <title>
    <asp:ContentPlaceHolder ID="title" runat="server">
    </asp:ContentPlaceHolder>
        </title>
    <asp:ContentPlaceHolder ID="Header" runat="server">
    </asp:ContentPlaceHolder>
    <!--Style Sheet-->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css" integrity="sha512-Evv84Mr4kqVGRNSgIGL/F/aIDqQb7xQ2vcrdIwxfjThSH8CSR7PBEakCr51Ck+w+/U6swU2Im1vVX0SVk9ABhg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link href="Style.css" rel="stylesheet" />
</head>
<body>
    <form id="form1" runat="server">
        <div class="grid-container">
         <!--danz flower shop Company Logo-->
    <div class="logo"> <img src="imgs/logo2.jpg" alt="Danz Flower Shop Logo" width="190" height="190"/>

    </div>

     <div class="header">

         <!--danz flower shop Company Information-->
     <h1 style="color:blue;font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', 'Arial', 'sans-serif'; text-align:center">DANZ FLOWER SHOP</h1>
     <h2 style="text-align:center">
         <b>1234 South East Avenue 
         Kgn 20</b>
     </h2>
     <h3 style="text-align:center">
         Tele:876-765-4321 <br />
         email:flowers@danflowershop.com
     </h3>
         <hr />
 </div>
    <div class="nav"><!--Navigation bar-->
        <ul>
            <li><a href="contact.aspx"><i class="fa-solid fa-phone"></i> CONTACT</a></li>
            <li><a href="home.aspx"><i class="fa-solid fa-house"></i>  HOME</a></li>
            <li><a href="about_us.aspx"><i class="fa-solid fa-user"></i>  ABOUT US</a></li>
        </ul>
    </div>

    <div class="content">
    <asp:ContentPlaceHolder ID="ContentPlaceHolder2" runat="server">
 </asp:ContentPlaceHolder>
            </div>

    <div class="footer"><!--Footer-->
        <hr />
        <p style="text-align:center">
        Danz Flower Shop, LLC <br /> 
            <small>All products are license Under a tride right agreement <br />
                &copy; 2025 DANZ FLOWER SHOP. All rights reserved.
            </small>

        </p>
    </div>
</div>
    </form>
</body>
</html>
