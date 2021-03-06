Blockgröße für Stützstruktur
====
Wenn der Support [in Blöcke aufgeteilt](support_skip_some_zags.md) ist, bestimmt diese Einstellung, wie groß die einzelnen Blöcke des Supports sein werden.

<!--screenshot {
"image_path": "support_skip_some_zags.png",
"models": [{"script": "rack.scad"}],
"camera_position": [0, 184, 10],
"settings": {
    "support_enable": true,
    "support_pattern": "zigzag",
    "support_skip_some_zags": true,
    "support_skip_zag_per_mm": 20
},
"colours": 32
}-->
![Jeder Block ist etwa 20 mm breit.](../../../articles/images/support_skip_some_zags.png)

Kleinere Stücke lassen sich in der Regel leichter entfernen als größere Stücke. Es gibt weniger Oberfläche, die am Modell haften bleibt, so dass weniger Kraft erforderlich ist, um den Support zu entfernen. Wenn das Entfernen des Supports also normalerweise nicht schwierig ist, kann das Entfernen des Supports mehr Arbeit machen. Jedes Stück muss dann einzeln entfernt werden, anstatt die gesamte Stütze in einem großen Stück zu entfernen.

Wenn die Stücke sehr klein sind, kann die strukturelle Integrität des Supports beeinträchtigt werden. Das Muster des Supports ähnelt dann mehr dem Linienmuster, was die Gefahr des Umkippens erhöht. Dies würde zu mehr stringing und einer schlechteren Überhangqualität an den Stellen führen, an denen der Support umkippt.