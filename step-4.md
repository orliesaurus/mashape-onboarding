#Consuming an API

Each API has its own page, where different tabs are shown:

* Documentation: This area is dedicated to the documentation of the API by the provider, here endpoints and various parameters are listed.
* Pricing: Each API can be monetized through Mashape. An API Provider can set up monetization through the pricing page, while consumer can pick a pricing plan according to their needs from the ones available under this tab
* Overview: An overview of the API, as defined by the API provider.
* Status: The status of the API, it's uptime and latency.
* Announcements: A place where the provider can announce changes to its API, along with various Terms of Service.
* API Support: The first line of support for an API. API Consumers can open public or private tickets with the provider.

###Documentation tab
The documentation is the heart of one's API and probably the most interesting part of APIs hosted on Mashape.

<p class="image-center"><img width="100%" src='/imgs/documentation-tab.png'></p>

* * *
1. On the left hand side a listing of all endpoints. Endpoints come ordered in functional groups when the provider specifies so.
2. On the middle of the page you can find all API parameters to perform and test endpoints. Note that you might have to change these according to what you want to achieve. Here are listed general instructions and description for each endpoint that will help you consume the API. Remember the Mashape Application you created in the previous step? When testing an endpoint you can select it from the dropdown menu from within this section. When navigating back to the dashboard and your application you will see statistics and analytics appear.
3. On the right hand side you can find the request generator. Simply select your choice of programming language and the same request will appear as a code snippet.

###Pricing tab
The pricing tab is where API consumers go to choose a consumption plan and where API providers define how to price their API.

There are two types of plans:

* Normal Plans
* Private Plans

#### • Normal Plans

The default view when on the pricing tab, as a provider you can customise each plan with a base price. You can have up to 4 default plans at one time. (Basic, Pro, Ultra, Mega)

**Quotas**:

You can specify limits *per endpoint call* (this is awesome!) per plan: <br>
For example your basic plan might restrict access to only 3 out of 5 of your API's endpoints and with 1000 calls per day each

**Features**:
You can add extra feature that you will be giving to your customers that subscrine to that plan.
For example, phone support, legacy access ...or chocolate cookies.

#### • Private plans

These are just like normal plans in terms of setup, but unlike them they're not available to everyone. This means they will be invisible to the public. As a provider need to invite developers to consume these plans: You can do that using the "Send Plan" button.

###Overview tab
A tab only visible if the API provider adds content to it.

1. In the overview tab you can add headlines that give a general overview of what your API is all about.
2. You can also add your custom API Terms of usage.


<p class="image-center"><img width="100%" src='/imgs/overview-tab.png'></p>


###Status tab

Self explanatory tab, with basic analytics regarding the health of the API.

###Announcements tab
Similar to the Overview tab in a way that is visible only if the provider writes one or more announcements to communicate with the community of developers on Mashape.

###API Support tab

Here you can submit and collaborate on any issue you or others might have with an API.
Simply add an issue by completing the mandatory fields (you can use Markdown).
Issues can be private if you only want the provider to see them (for example if you want to share somewhat confidential data that you would like to keep away from the eyes of the public)
You can use the issue search function to filter out certain types of issues by name.

- - -