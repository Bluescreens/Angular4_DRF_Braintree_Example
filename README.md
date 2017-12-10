# About **Angular4\_DRF\_Braintree\_Example**

This is a simple example on how to use [Braintree](https://www.braintreepayments.com/) with [Angular4](https://angular.io) and [Django Rest Framework](http://www.django-rest-framework.org). We use [Hosted Fields](https://developers.braintreepayments.com/guides/hosted-fields/overview/javascript/v2) for the integration. You should check the [Braintree JS Client SDK](https://developers.braintreepayments.com/guides/client-sdk/setup/javascript/v2) and the [Braintree Python Server SDK](https://developers.braintreepayments.com/start/hello-server/python) before you continue.

## Getting Started

The following instructions will get you a copy of this project up and running on your local machine for development and testing purposes.

### Download

```
git clone git@github.com:Bluescreens/Angular4_DRF_Braintree_Example.git
cd Angular4_DRF_Braintree_Example
```

### Prerequisites

* python: 3.6.3


```
pip install -r requirements.txt
```

### Installation

* Use your braintree credentials [here]()

```
cd client
npm install && ng built
cd ../server
python manage.py runserver
```

## Contributing

* Any contribution that will enchance the current project is welcomne.
* If you have any question about this project you can open an issue.
* If you spot any kind of bug or you have a suspicion of a bug that may occur please let us know by opening an issue.
* If you want to contribute to this project just create a pull request.

## Author

[**Stefanos Chaliasos**](https://github.com/StefanosChaliasos)

## Licence

This project is licensed under the  - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Special thanks to professor Panos Louridas for his contribution to [payment.component.ts]().
* You could check for more examples about internet cloud apps (Angular, Django, DRF, Flask, nginx, nodejs) [here](https://github.com/louridas/internet_cloud_apps)
