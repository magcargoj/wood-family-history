# Family Tree

Below is an interactive, collapsible visualization of the merged family lineages. 

### 🌳 Interactive Tree
*Click on any node to expand or collapse the next generation.*

<div id="family-tree" class="tree-container"></div>

<script src="tree.js"></script>
<script>
  // Delay slightly to ensure D3 is loaded and container is ready
  setTimeout(() => {
    if (typeof renderTree === 'function') {
      renderTree('#family-tree', 'Website Data/tree_data.json');
    }
  }, 500);
</script>

---

## Direct Lineage (Static Reference)

The following text-based tree provides a high-level overview of the major branches.

```
[[Jeremy_Wood]] (b. 1992)
├── Spouse: [[Ashley_Jordan_Brooks]] (b. 1993) (Siblings: [[Kevin_Scott_Brooks_Jr]] (b. 1996), [[Jamie_Lynne_Emory]], [[Jessica_Rae_Brooks]])
│   ├── [[Kevin_Scott_Brooks_Jr]] (b. 1996) & [[Logan_Beasley]]
│   │   └── [[Natalie_Brooks]] & [[Malcolm_Brooks]]
│   ├── [[Kevin_Scott_Brooks_Sr]] (b. 1967)
│   │   ├── [[Henry_Calvin_Brooks]] (b. 1935)
│   │   │   ├── [[Joseph_Orren_Brooks]] (1899-1971) & [[Lena_Tuggle]] (1909-2001)
... (rest of static tree)
```
