
# Rendering stream:
    1. Create new version of component;
    2. Compare with the previous version;
    3. If there are changes, will update what changed.


# When use memo:
    1. Pure Functional Components (Functions that always return the same result);
    2. Renders too often;
    3. Re-renders with same props;
    4. Medium to big size.

# When use useMemo:
    1. Avoid recalculating something unnecessarily (Heavy calculations);
    2. Referential equality (When we pass that information to a child component).

    Obs: Referential equality is when you want to compare whether an object is the same, and not exactly whether its value is the same.



<!-- async function showFormattedDate() {
    const { format } = await import('date-fns')

    format()
}
     -->