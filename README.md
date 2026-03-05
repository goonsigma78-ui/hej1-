 (cd "$(git rev-parse --show-toplevel)" && git apply --3way <<'EOF' 
diff --git a/README.md b/README.md
new file mode 100644
index 0000000000000000000000000000000000000000..ff733e6d36d63e0179f7962fd0cbb92c987e250d
--- /dev/null
+++ b/README.md
@@ -0,0 +1,20 @@
+# Minecraft: Oak Biome (spelbar idé)
+
+Det här projektet beskriver en enkel spelidé för ett **oak biome**-läge i Minecraft-tema.
+
+## Mål
+Spelaren ska kunna spela i en värld med fokus på ek-skog (oak), samla resurser och överleva.
+
+## Grundfunktioner
+- Start i ett oak-biome-inspirerat område.
+- Samla trä, sten och mat.
+- Bygg skydd innan natten.
+- Enkla uppdrag: bygg arbetsbänk, skapa verktyg och odla mat.
+
+## Vinstvillkor (förslag)
+- Bygg ett tryggt basområde.
+- Ha stabil matproduktion.
+- Klara tre nätter i rad.
+
+## Kommentar
+Om du menade något annat med "minecraft oak biome man ska kunna spela", skriv gärna en mer exakt kravlista.
 
EOF
)
