# voltpulse-version-bump-demo

Throwaway demonstration of the voltpulse-edge #18 auto-version pipeline.
Every push to `main` recomputes `X.Y`: `feat:`→X (reset Y), everything else→Y
(fix/enhancement or no-signal default). SoT = annotated git tags `vX.Y`.
