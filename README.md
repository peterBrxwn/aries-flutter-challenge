

## Objective

Design and implement an iOS & Android front-end for options strategy risk and reward analysis using Flutter.

## Brief

Your challenge is to create a Flutter component that can generate a risk & reward graph for options strategies. The component should accept an input of up to four options contracts and output the following:
1. A risk & reward graph where X is the price of the underlying at the time of expiry and Y is the profit/loss at that price. 
2. Max profit, max loss, and all break even points.

### Evaluation Criteria

- Completeness of the logic
- Usability of the graph
- Aesthetics of the UI
- Readability and code structure

### CodeSubmit 

Please organize, design, test, and document your code as if it were
going into production - then push your changes to the main branch.

Reply to the invitation e-mail with your github username to notify of completion.

Have fun coding! 🚀
The Aries Financial Team

### Solution

#### Requirements

- Flutter version 3.22.2
- Dart 3.4.3
- DevTools 2.34.3
- Flutter sdk environment: '>=3.3.0 <4.0.0'

#### Getting Started

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

Run `flutter pub get;` to download dependencies.

Build the application by running `flutter run;`
or from the run and debug sidebar, click run icon.

#### Testing

##### Unit tests

```bash
flutter run test/unit_test.dart;
```

##### Integration tests

```bash
flutter run test/widget_test.dart;
```

NB: There was no need to used state management (e.g BLoC), dependency injection etc for this solution.

###### 1

Entry cost: $1,105.00
Maximum risk: $1,105.00 (at $100.00)
Maximum return: infinite (on upside)
Max return on risk: N/A
Breakevens at expiry: $111.05

###### 2

Entry cost: $1,305.00
Maximum risk: $1,305.00 (at $102.50)
Maximum return: infinite (on upside)
Max return on risk: N/A
Breakevens at expiry: $115.55

###### 3

Entry credit: $1,475.00 net credit
Maximum risk: $8,825.00 (at $0.00)
Maximum return: $1,475.00 (at $103.00)
Max return on risk: 16.7% (2034% ann.)
Breakevens at expiry: $88.25
Probability of profit: 100% 

###### 4

Entry cost: $1,700.00
Maximum risk: $1,700.00 (at $105.00)
Maximum return: $8,800.00 (at $0.00)
Max return on risk: 517.6% (62980% ann.)
Breakevens at expiry: $88.00

###### Screenshot:

<img src="/assets/screenshots/1.png" width=270>
