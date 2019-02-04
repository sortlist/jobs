![Sortlist listing](https://i.ibb.co/MSycDT1/Capture-d-cran-2019-02-01-15-05-47.png)

# Sortlist Integration Challenge

[Sortlist](https://www.sortlist.com) is not just a beautiful interface, it’s a full experience with a deep integration from the user interface all the way to the servers we interact with. As Sortlist’s backbone, the development is crucial to every aspect of our web application and client apps rely heavily on it.

That’s why we’re looking for a talented Engineer to join our highly motivated development team and help us build Sortlist inside out. As Mom used to say, beauty comes from within.

### Description

For this challenge, you'll be asked to create a **Sortlist branded page using the framework from AngularJS Material**.

As Sortlist apps have been built upon the same framework, it is crucial to understand the Angular Material System specifications and constraints. If you are not familiar with the Angular Material Framework, start by having a look at the doc here: [AngularJS Material Documentation](https://material.angularjs.org/latest/getting-started).

On this brand new page, you'll have to display a [list of agencies in the form of cards](https://invis.io/GMQAPBAXC2H#/344421089_Public-Longtail). Each of these agencies would have multiple properties that you would have to assemble and display in a fashion way.

### Layout

To help you in this task, we crafted a special [designed layout](https://invis.io/GMQAPBAXC2H#/344421089_Public-Longtail) of how this page should look like.

**This page should be structured as followed:**
- A navbar including navigation items.
- A scrollable body including the agencies list using cards and a grid system.

To bootstrap your page, just follow the same HTML structure as the one from this [CodePen](https://codepen.io/team/AngularMaterial/pen/RrbXyW.).

### Technical specifications

#### Agencies properties

`agency.name` `agency.logo` `agency.location` `agency.cover` `agency.reviews` `agency.works` `agency.team` `agency.services` `agency.phone`

Use [controllers](https://docs.angularjs.org/guide/controller) to display those properties in your page. A controller is a JavaScript object that contains attributes/properties, and functions. Each controller accepts $scope as a parameter, which refers to the application/module that the controller needs to handle. Here is an example:

`.controller('AppCtrl', function($scope) {

    $scope.phones = [
      {
        type: 'Home',
        number: '(555) 251-1234',
        options: {
          icon: 'communication:phone'
        }
      },
      {
        type: 'Cell',
        number: '(555) 786-9841',
        options: {
          icon: 'communication:phone',
          avatarIcon: true
        }
      },
      {
        type: 'Office',
        number: '(555) 314-1592',
        options: {
          face : imagePath
        }
      },
      {
        type: 'Offset',
        number: '(555) 192-2010',
        options: {
          offset: true,
          actionIcon: 'communication:phone'
        }
      }
    ];
`

#### Requirements

- The HTML should match the AngularJS Material guidelines and avoid unecessary elements that are not provided by the AngularJS Material library.
- The CSS should be as short as it could be and used with caution to avoid useless overiding. Writing your code in SASS is a plus.
- The overall look & feel should match perfectly the provided layout and our Sortlist Design Guidelines.
- Make sure the layout is responsive.

### Resources

- [AngularJS material Documentation](https://material.angularjs.org/latest/getting-started)
- [Material Design Guidelines](https://material.io/design/)
- [Sortlist Design Guidelines](https://projects.invisionapp.com/boards/QC3A0ELUWN23S/)
- [Designed layout for the Challenge](https://invis.io/GMQAPBAXC2H#/344421089_Public-Longtail)
