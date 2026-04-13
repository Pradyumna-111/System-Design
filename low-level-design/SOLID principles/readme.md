# SOLID Principles

SOLID principles are five design principles that help make software more maintainable, scalable, and flexible.

---

## 1. Single Responsibility Principle (SRP)

A class should have only one reason to change.

✅ Example:

* `Vehicle` class only holds vehicle data
* `Payment` class handles fee calculation

❌ Bad:

* One class handling parking + payment + ticket

---

## 2. Open/Closed Principle (OCP)

Open for extension, closed for modification.

✅ Example:

* Add new pricing strategies without modifying existing code

---

## 3. Liskov Substitution Principle (LSP)

Subclasses should replace base classes without breaking behavior.

✅ Example:

* `Bike`, `Car`, `Truck` should behave consistently as `Vehicle`

---

## 4. Interface Segregation Principle (ISP)

Clients should not depend on unused interfaces.

✅ Example:

* Separate `ParkingStrategy` and `PaymentStrategy`

---

## 5. Dependency Inversion Principle (DIP)

Depend on abstractions, not concrete classes.

✅ Example:

* Use `PricingStrategy` interface instead of hardcoding logic

---

## Summary

| Principle | Goal                     |
| --------- | ------------------------ |
| SRP       | One responsibility       |
| OCP       | Extend without modifying |
| LSP       | Replace safely           |
| ISP       | Small interfaces         |
| DIP       | Depend on abstractions   |
