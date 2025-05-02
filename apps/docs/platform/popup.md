# Popup

![Popup](./components/popup.png)

The **Popup** is a component displayed on top of the Mini App. Its primary use case is to request user confirmation before performing an action.

Telegram Mini Apps support popups with a customizable title, message, and up to 3 configurable buttons.

To display a popup, developers can use the [web_app_open_popup](methods.md#web-app-open-popup) method. When a user clicks a button in the popup, the Telegram application emits the [popup_closed](events.md#popup-closed) event, passing the identifier of the clicked button.
