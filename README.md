# Create-assert_eq-
fn додати(a: i32, b: i32) -> i32 {     a + b } #[cfg(test)] mod tests {     use super::*;      #[test]     fn тест_додавання() {         assert_eq!(додати(2, 3), 5);     }
