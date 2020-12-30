# Create SubMenu

- Create SubMenu
    - [Create a menu](#create-submenu.md)
    - [Settings available](/docs/menu-settings.md)
    
<a name="create-submenu"></a>
### Create a SubMenu

To create your menu we will use the [RMenu](/docs/rmenu.md) utility provided with RageUI, if you want to understand how it works I invite you to check by yourself on the documentation.

    RMenu.Add('showcase', 'submenu', RageUI.CreateSubMenu(RMenu:Get('showcase', 'main'), "RageUI", "showcase"))
