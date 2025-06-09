# Setting Up Your MCP Server for UClone Integration

This guide will walk you through connecting any MCP (Master Control Program) server with your UClone environment. While Zapier is used as an example, the principles apply to any MCP server that supports an SSE (Server-Sent Events) connection. Our focus here is on configuring your UClone service to successfully integrate with these servers.

---

## 1. Access Your MCP Server

First, you'll need to log in to or access your chosen MCP server. The specific steps will depend on your MCP server provider.

* **Log in/Access:** Go to your **MCP server's platform or interface**. (For example, if you're using Zapier, you'd go to `https://zapier.com/` and then navigate to their MCP section, typically found at `https://mcp.zapier.com/mcp/servers`.)
* **Create a New MCP Server Instance:** On your MCP server's platform, you'll likely need to **create a new MCP Server instance**. This might involve naming it (e.g., "UClone Integration") and selecting a client type (if applicable, "other" is often a generic choice).

---

## 2. Configure Tools on Your MCP Server

This is where you define the specific functionalities and applications you want UClone to access through your MCP server.

1.  **Add Tools:** Within your MCP server's configuration, look for an option to **add tools, apps, or integrations**.
2.  **Select Integrations:** Choose the specific services (e.g., Google Calendar, Slack, your custom internal tools) that you want to expose to your UClone environment via this MCP server.
    * **Example:** If using Zapier, you'd click "+ Add Tool" and search for an app like "Google Calendar: Find Multiple Events."

---

## 3. Obtain the SSE Connection URL

The core of connecting your MCP server to UClone is getting its unique Server-Sent Events (SSE) connection URL. This URL allows UClone to receive updates and commands from your MCP server.

1.  **Locate Connection Settings:** On your MCP server's configuration page, find the **connection or integration settings**. This is often labeled "Connect," "API," or similar.
2.  **Copy the SSE URL:** There should be an option to **copy a URL** specifically designed for real-time connections, often referred to as an SSE URL or webhook URL.
    * **Example:** In Zapier, this is found under the "Connect" tab, where you'd click "Copy URL."

---

## 4. Integrate with Your UClone Service

Now, let's bring that URL into your UClone environment and define the access scope for your tools.

1.  **Go to Clone Studio:** Navigate to your **Clone Studio environment**.
2.  **Access MCP Settings:** Find the **MCP Setting section**.
3.  **Paste the URL:** Paste the **copied SSE connection URL** from your MCP server into the designated input field (usually an upper box) within UClone's MCP Settings.
4.  **Define Tool Scope (Crucial for Access Control):** This determines who can use the tools exposed by your MCP server within a clone. Check the appropriate boxes based on your needs:
    * **Owner:** If checked, the tools provided by this MCP server will be active and usable only when the **creator** (or owner) of the clone is interacting with it.
    * **User:** If checked, the tools provided by this MCP server will be active and usable when **any other user** (not just the creator) interacts with the clone.
    * *You can check both "Owner" and "User" if you want the tools to be available to everyone.*
5.  **Enable MCP:** Finally, **enable MCP** within your UClone environment by clicking the relevant toggle or checkbox (often labeled "Enable MCP" in the Features section).

---

## 5. Test Your Integration!

Your MCP server should now be configured and ready to communicate with your UClone environment. Go ahead and **try using one of the tools** you added to your MCP server from within your clone to ensure everything is working correctly!
