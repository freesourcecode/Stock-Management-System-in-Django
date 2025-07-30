# Stock Management System Project in Django with Source Code

The **Stock Management System Project in Django** created based on **python**, **Django**, and **SQLITE3 Database**.

This project is ideal for measuring your business, and it is appropriate for any form of business that sells products rather than services.

This system generates a detailed list of all reviews written by the administrator.

A corporation or business may use the system to track their products/stocks, sales transactions, and other related transactions.

Reports such as the Sales Report, Return of Goods Report, and others are produced by this project.

>[!NOTE]
>To start creating a **Stock Management System Project in Python Django**, makes sure that you have PyCharm Professional IDE Installed in your computer.

## Admin Features of Stock Management System Project in Django

* **Login Page**

The page where the system administrator enters their system credentials in order to gain access to the system’s administrative side.

* **Manage Product**

This is the page where an administrator can add, update, and delete product information.

* **Manage Brand**

This is the page where an administrator can add, update, and delete brand information.

* **Categories Management**

This is the page where an administrator can add, update, and categories information.

* **Manage Order**

This is the page where an administrator can add, update, view order and delete order information.

* **Manage Report**

The page where admin can view the daily sales report.

## How to Create a Project Stock Management System Project in Django?

Here are the steps on how to create a Stock Management System Project in Django with Source Code.

1. **Open file**.

First, open “pycharm professional” after that click “file” and click “new project”.

<img width="484" height="453" alt="image" src="https://github.com/user-attachments/assets/92f7b737-9222-4dbc-a6b2-ec0387cad7de" />

2. **Choose Django**.

Next, after click “new project“, choose “Django” and click.

<img width="152" height="325" alt="image" src="https://github.com/user-attachments/assets/3e820fc8-d038-4ede-9f40-2a447e6f9197" />

3. **Select file location**.

Then, select a file location wherever you want.

4. **Create application name**.

After that, name your application.

5. **Click create**.

Lastly, finish creating project by clicking “create” button.

<img width="802" height="489" alt="image" src="https://github.com/user-attachments/assets/b2511d59-5d2b-4de4-9df4-74bd64948bc5" />

6. **Start Coding**.

Finally, we will now start adding functionality to our Django Framework by adding some functional codes.

## Functionality and Codes of the Stock Management System Project in Django

* **Create template for the navigation bar in Stock Management System Project Project in Django**.

In this section, we will learn on how create a templates for the navigation bar. 

To start with, add the following code in your navbar.html under the folder of /templates/modules.

```
<nav class="navbar navbar-toggleable-lg" style="background-color: black; box-shadow: 0 0px 0px 0 rgba(0, 0, 0, 0.2), 0 2px 20px 0 rgba(0, 0, 0, 0.19)">
            <a class="navbar-brand" href="{% url 'index' %}">STOCK MANAGEEMNT SYSTEM</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
                    aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>

            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="nav navbar-nav ml-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="{% url 'dashboard' %}"><i class="fa fa-list-alt" aria-hidden="true"></i> Dashboard</a>
                    </li>
                    <li class="nav-item" id="navBrand">
                        <a class="nav-link" href="{% url 'products' %}"><i class="fa fa-gamepad" aria-hidden="true"></i></i> Products</a>
                    </li>
                    <li class="nav-item" id="navBrand">
                        <a class="nav-link" href="{% url 'brand' %}"><i class="fa fa-envira" aria-hidden="true"></i> Brands</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="{% url 'categories' %}"><i class="fa fa-list" aria-hidden="true"></i> Categories</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="{% url 'orders' %}"><i class="fa fa-cubes" aria-hidden="true"></i></i> Orders</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="{% url 'report' %}"><i class="fa fa-line-chart" aria-hidden="true"></i></i> Report</a>
                    </li>
                </ul>
                {% if user.is_authenticated %}
                <ul class="nav navbar-nav navbar-right">
                    <li class="dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button"
                           data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                               <i class="fa fa-user" aria-hidden="true"></i>
                        </a>
                        <ul class="dropdown-menu dropdown-menu-right">
                            <div class="dropdown-item" style="color: cornflowerblue">{{ user|capfirst }}</div>
                            <a class="dropdown-item" href="#">Settings</a>
                            <a class="dropdown-item" href="{% url 'logout' %}">Logout</a>
                            <div class="dropdown-divider"></div>
                            <a class="dropdown-item" href="#">Something else here</a>
                        </ul>
                    </li>
                </ul>
                {% endif %}

            </div>
        </nav>
```


### 📌 Here's the full documentation for the [Stock Management System Project in Django](https://itsourcecode.com/free-projects/python-projects/stock-management-system-project-in-django-with-source-code/)


