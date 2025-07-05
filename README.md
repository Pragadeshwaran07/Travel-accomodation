# Travel-accomodation
Developed a comprehensive travel management application enabling users to handle flights and accommodations with advanced filtering/sorting capabilities. Implemented OOP design with Java 17, leveraging lambda expressions for dynamic filtering (e.g., "Show flights under $300" or "Hotels with pools"). Created generic comparators to sort travel options by price/ratings and validated functionality through JUnit tests, achieving 90%+ test coverage. Highlights: Stream API, JUnit, OOP principles, and clean modular architecture.*

This Java application simulates a travel booking system that allows users to:

✅ Manage flights (add/remove, filter by price, sort by price/ratings)
✅ Manage accommodations (filter by amenities, sort by price/ratings)
✅ Compare travel options using flexible comparators
✅ Demonstrate core OOP principles and lambda expressions
✅ Validate functionality through JUnit tests

## Features
- **Flight Management**: 
  - Add/remove flights
  - Filter flights by price (e.g., < $300)
  - Sort by price, departure time, or ratings
- **Accommodation Management**:
  - Add/remove hotels
  - Filter by amenities (e.g., "Pool", "Breakfast")
  - Sort by price/night or ratings
- **Comparator System**: Generic comparators for sorting flights/hotels by price or ratings
- **Full Test Coverage**: JUnit tests for all core functionality

## Tools and Technologies
- **Java JDK 17+**
- **JUnit 4** (for unit testing)
- **Git** (for version control)

  ## Sample Output
```
All Flights:
Flight{id='F1', airline='Delta', ...}
Flight{id='F2', airline='United', ...}
Hotels with Pool amenity:
Accommodation{id='A2', name='Beach Resort', ...}
```


## Key Highlights
- **Lambda Expressions**: Used for filtering/sorting (e.g., `flight -> flight.getPrice() < 300`)
- **Generic Comparators**: Single comparator handles both flights/hotels
- **OOP Design**: Separation of entities, services, and comparators
- **JUnit Testing**: 90%+ test coverage for core logic
