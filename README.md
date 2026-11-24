
# Awesome Blender Characters

![Blender](https://img.shields.io/badge/Blender-3D%20character%20creation-E87D0D?logo=blender&logoColor=white)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A focused catalog of resources for creating, rigging, animating, and presenting 3D characters in [Blender](https://www.blender.org/). It covers the full path from reference and blockout to finished animation, with an emphasis on tools that work well inside Blender's 3D editor.

## Contents

- [Start Here](#start-here)
- [Blender Editor Essentials](#blender-editor-essentials)
- [Character Creation](#character-creation)
- [Rigging and Deformation](#rigging-and-deformation)
- [Character Animation](#character-animation)
- [Tools and Add-ons](#tools-and-add-ons)
- [Assets and References](#assets-and-references)
- [Learning](#learning)
- [Production Resources](#production-resources)
- [Community](#community)
- [Character Workflow Checklist](#character-workflow-checklist)
- [Contributing](#contributing)

## Start Here

### The Character Pipeline

| Stage | Goal | Useful Blender features |
| --- | --- | --- |
| Reference | Define proportions, style, and expression | Image Empty, Grease Pencil, Collections |
| Blockout | Establish readable silhouette and pose | Primitives, Mirror, Subdivision Surface |
| Sculpt or model | Build anatomy, clothing, and secondary forms | Sculpt Mode, Multiresolution, Shrinkwrap |
| Retopology and UVs | Prepare a clean, deformable production mesh | Snap, Quad Remesh, UV Editor |
| Look development | Create skin, eyes, hair, and clothing materials | Shader Editor, Texture Paint, Geometry Nodes |
| Rigging | Build controls for body and face | Armatures, Constraints, Drivers, Rigify |
| Skinning | Make the mesh deform cleanly | Armature modifier, Weight Paint, Corrective Shape Keys |
| Animation | Create poses, timing, and performance | Dope Sheet, Graph Editor, NLA Editor |
| Presentation | Light, render, and deliver the character | Eevee or Cycles, Compositor, Sequencer |

### A Good First Project

Start with a stylized character rather than a highly detailed realistic human. Finish one complete model with a simple facial rig, a short walk or acting shot, and a clean render. A finished small project teaches more than an unfinished sculpt.

## Blender Editor Essentials

### Official Documentation

- [Blender](https://www.blender.org/) - The official application site and download page.
- [Blender Manual](https://docs.blender.org/manual/en/latest/) - The complete user manual.
- [Blender API Reference](https://docs.blender.org/api/current/) - Python API documentation for tools and automation.
- [Blender Developer Documentation](https://developer.blender.org/docs/) - Development notes, design tasks, and technical documentation.
- [Blender Extensions](https://extensions.blender.org/) - The official catalog for Blender extensions and add-ons.
- [Blender Studio Training](https://studio.blender.org/training/) - Production-focused courses and workflow breakdowns.
- [Blender Studio Films](https://studio.blender.org/films/) - Open production files, films, and behind-the-scenes material.

### Editors and Workspaces

- [3D Viewport](https://docs.blender.org/manual/en/latest/editors/3dview/index.html) - Model, sculpt, pose, and inspect the character in 3D.
- [Outliner](https://docs.blender.org/manual/en/latest/editors/outliner/index.html) - Keep meshes, rigs, controls, collections, and assets organized.
- [Properties Editor](https://docs.blender.org/manual/en/latest/editors/properties_editor.html) - Configure modifiers, materials, particles, physics, and scene settings.
- [Shader Editor](https://docs.blender.org/manual/en/latest/editors/shader_editor.html) - Build reusable skin, eye, hair, and fabric shaders.
- [Image Editor](https://docs.blender.org/manual/en/latest/editors/image/index.html) - Inspect UVs, paint textures, and compare reference images.
- [Dope Sheet](https://docs.blender.org/manual/en/latest/editors/dope_sheet/index.html) - Block poses and manage keyframe timing.
- [Graph Editor](https://docs.blender.org/manual/en/latest/editors/graph_editor/index.html) - Refine arcs, spacing, ease, and overlapping motion.
- [NLA Editor](https://docs.blender.org/manual/en/latest/editors/nla/index.html) - Layer and reuse animation actions.
- [Asset Browser](https://docs.blender.org/manual/en/latest/editors/asset_browser.html) - Reuse poses, materials, collections, and character parts.

### Non-destructive Modeling

- [Modifiers](https://docs.blender.org/manual/en/latest/modeling/modifiers/index.html) - Use procedural operations instead of permanently editing the base mesh.
- [Mirror Modifier](https://docs.blender.org/manual/en/latest/modeling/modifiers/generate/mirror.html) - Model symmetrical characters efficiently.
- [Subdivision Surface](https://docs.blender.org/manual/en/latest/modeling/modifiers/generate/subdivision_surface.html) - Preview a smooth character while retaining a manageable cage.
- [Shrinkwrap Modifier](https://docs.blender.org/manual/en/latest/modeling/modifiers/deform/shrinkwrap.html) - Project clothing, retopology, or details onto a sculpt.
- [Geometry Nodes](https://docs.blender.org/manual/en/latest/modeling/geometry_nodes/index.html) - Build procedural hair, clothing details, crowds, and reusable character systems.
- [Collections and View Layers](https://docs.blender.org/manual/en/latest/scene_layout/collections/index.html) - Separate body, clothing, controls, render, and reference content.

## Character Creation

### Reference and Design

- [PureRef](https://www.pureref.com/) - Lightweight reference-board application for concept art and turnaround sheets.
- [Linger](https://withlinger.com/) - Apple Silicon Mac app for organizing character references with source links and notes, then arranging selected images on a project canvas. Paid, with a free trial.
- [Line of Action](https://line-of-action.com/) - Timed drawing and pose reference for gesture and anatomy practice.
- [Sketchfab](https://sketchfab.com/) - Inspectable 3D references for anatomy, clothing, props, and historical design.
- [ArtStation](https://www.artstation.com/) - Character art, concept design, and professional portfolio reference.
- [Blender Grease Pencil](https://docs.blender.org/manual/en/latest/grease_pencil/index.html) - Draw turnarounds, notes, and 2D design directly in a Blender scene.

### Modeling and Sculpting

- [Modeling](https://docs.blender.org/manual/en/latest/modeling/index.html) - Blender's modeling reference, including meshes, curves, surfaces, and modifiers.
- [Sculpting](https://docs.blender.org/manual/en/latest/sculpt_paint/sculpting/index.html) - Brushes, masking, posing, symmetry, and sculpt workflow.
- [Multiresolution Modifier](https://docs.blender.org/manual/en/latest/modeling/modifiers/generate/multiresolution.html) - Sculpt high-resolution detail while preserving lower subdivision levels.
- [Sculpt Mode Masking](https://docs.blender.org/manual/en/latest/sculpt_paint/sculpting/editing/mask.html) - Isolate face, clothing, anatomy, and other sculpt regions.
- [Sculpt Brushes](https://docs.blender.org/manual/en/latest/sculpt_paint/sculpting/brushes/brushes.html) - Explore the sculpt brushes used for broad forms and detailing.
- [Retopology](https://docs.blender.org/manual/en/latest/modeling/meshes/retopology.html#retopology) - Rebuild a sculpt into a clean animation-ready mesh.
- [Quad Remesh](https://docs.blender.org/manual/en/latest/modeling/meshes/retopology.html) - Quickly generate a starting topology that can be cleaned by hand.
- [Quad Remesher](https://exoside.com/quadremesher/) - Automatic quad retopology tool with Blender integration, useful for turning sculpts into animation-friendly base meshes.
- [Poly Build Tool](https://docs.blender.org/manual/en/latest/modeling/meshes/tools/poly_build.html) - Manually rebuild clean topology over a sculpt with snapping.

### Topology and UVs

- [Mesh Structure](https://docs.blender.org/manual/en/latest/modeling/meshes/structure.html) - Understand normals and shading problems before they reach the final render.
- [UV Editing](https://docs.blender.org/manual/en/latest/modeling/meshes/uv/index.html) - Unwrap the body, face, clothing, and accessories for texture work.
- [UV Layout](https://docs.blender.org/manual/en/latest/modeling/meshes/uv/editing.html) - Place seams and pack islands for efficient texture resolution.
- [Texture Paint](https://docs.blender.org/manual/en/latest/sculpt_paint/texture_paint/index.html) - Paint masks, color, roughness, and hand-authored character details.
- [Bake](https://docs.blender.org/manual/en/latest/render/cycles/baking.html) - Transfer sculpt or procedural detail to production textures.

### Character Generators and Base Meshes

- [Human Generator](https://humgen3d.com/) - Parametric realistic-human generator with outfits, hair, poses, and expressions inside Blender.
- [MPFB](https://extensions.blender.org/add-ons/mpfb) - Free MakeHuman-based human generator and editor with Rigify support.
- [MB-Lab](https://mblab.community/) - Open character generation and rigging tools for Blender.
- [MakeHuman](https://www.makehumancommunity.org/) - Open human base meshes and character-generation workflow.
- [Daz to Blender Bridge](https://www.daz3d.com/daz-to-blender-bridge) - Transfer Daz characters, morphs, and materials into Blender.
- [KeenTools FaceBuilder](https://keentools.io/) - Build a head mesh from photo reference for likeness work and face-tracked characters.

### Materials, Hair, and Clothing

- [Materials](https://docs.blender.org/manual/en/latest/render/materials/index.html) - Material slots, surfaces, displacement, and viewport display.
- [Shader Nodes](https://docs.blender.org/manual/en/latest/render/shader_nodes/index.html) - Build skin, eyes, hair, leather, cloth, and stylized materials.
- [Subsurface Scattering](https://docs.blender.org/manual/en/latest/render/shader_nodes/shader/subsurface_scattering.html) - Add controlled light diffusion to skin, wax, and other soft materials.
- [Hair Curves](https://docs.blender.org/manual/en/latest/sculpt_paint/curves_sculpting/index.html) - Groom and sculpt modern curve-based hair systems.
- [Particle Hair](https://docs.blender.org/manual/en/latest/physics/particles/hair/index.html) - Use the legacy particle workflow for hair and fur where appropriate.
- [Cloth Simulation](https://docs.blender.org/manual/en/latest/physics/cloth/index.html) - Create secondary motion for garments, capes, and loose accessories.
- [Geometry Nodes Hair](https://docs.blender.org/manual/en/latest/modeling/geometry_nodes/hair/index.html) - Create procedural hair generation and styling systems.

## Rigging and Deformation

### Blender Fundamentals

- [Armatures](https://docs.blender.org/manual/en/latest/animation/armatures/index.html) - Bones, parenting, envelopes, and pose mode.
- [Armature Deform](https://docs.blender.org/manual/en/latest/animation/armatures/skinning/index.html) - Connect a mesh to a rig with automatic or manual weights.
- [Weight Paint](https://docs.blender.org/manual/en/latest/sculpt_paint/weight_paint/index.html) - Diagnose and correct deformation around joints.
- [Constraints](https://docs.blender.org/manual/en/latest/animation/constraints/index.html) - Build IK, aim, copy, limit, and space-switching behavior.
- [Drivers](https://docs.blender.org/manual/en/latest/animation/drivers/index.html) - Connect custom properties and controls to rig behavior.
- [Shape Keys](https://docs.blender.org/manual/en/latest/animation/shape_keys/index.html) - Create facial expressions and corrective deformations.
- [Corrective Smooth](https://docs.blender.org/manual/en/latest/modeling/modifiers/deform/corrective_smooth.html) - Improve troublesome bends after skinning.

### Rigging Systems

- [Rigify](https://docs.blender.org/manual/en/latest/addons/rigging/rigify/index.html) - Blender's bundled modular auto-rigging add-on.
- [CloudRig](https://projects.blender.org/Mets/CloudRig) - Blender Studio's rig-generation extension for production rigs.
- [CloudRig on Extensions](https://extensions.blender.org/add-ons/cloudrig/) - Installable CloudRig builds with version history and documentation links.
- [Auto-Rig Pro](https://blendermarket.com/products/auto-rig-pro) - Production-oriented rigging, retargeting, and export tool.
- [BlenRig](https://github.com/jpbouza/BlenRig) - Advanced free rigging system for Blender characters.
- [MB-Lab](https://mblab.community/) - Open character generation and rigging tools for Blender.
- [MakeHuman](https://www.makehumancommunity.org/) - Open human base meshes and character-generation workflow.
- [MPFB](https://static.makehumancommunity.org/mpfb.html) - MakeHuman plug-in for creating human characters inside Blender.

### Facial Animation

- [Faceit](https://faceit.io/) - Facial rigging, blendshape generation, and face capture workflow.
- [Shape Keys for Facial Animation](https://docs.blender.org/manual/en/latest/animation/shape_keys/index.html) - Use shape keys as a foundation for reusable expressions.
- [Rhubarb Lip Sync](https://github.com/DanielSWolf/rhubarb-lip-sync) - Free open-source tool for generating mouth-animation cues from dialogue audio.
- [Rigify](https://extensions.blender.org/add-ons/rigify/) - Rigify's extension page, including face-rig features and documentation links.

## Character Animation

### Animation Editors and Techniques

- [Animation](https://docs.blender.org/manual/en/latest/animation/index.html) - Blender's complete animation reference.
- [Keyframes](https://docs.blender.org/manual/en/latest/animation/keyframes/index.html) - Insert, edit, and manage animation keys.
- [Pose Library](https://docs.blender.org/manual/en/latest/animation/armatures/posing/editing/pose_library.html) - Save and reuse poses for blocking and production.
- [Inverse Kinematics](https://docs.blender.org/manual/en/latest/animation/armatures/posing/bone_constraints/inverse_kinematics/introduction.html) - Drive feet, hands, and other end-effectors naturally.
- [Animation Constraints](https://docs.blender.org/manual/en/latest/animation/constraints/index.html) - Maintain contacts, aiming, and relationships between controls.
- [Graph Editor](https://docs.blender.org/manual/en/latest/editors/graph_editor/index.html) - Polish timing, spacing, arcs, and overlap.
- [Dope Sheet and Action Editor](https://docs.blender.org/manual/en/latest/editors/dope_sheet/index.html) - Block and organize character performances.
- [NLA Editor](https://docs.blender.org/manual/en/latest/editors/nla/index.html) - Blend walks, gestures, loops, and reusable actions.
- [Motion Paths](https://docs.blender.org/manual/en/latest/animation/motion_paths.html) - Inspect arcs and trajectory while refining a pose or action.
- [Animation Retiming](https://docs.blender.org/manual/en/latest/editors/graph_editor/fcurves.html) - Adjust timing without rebuilding the entire performance.

### Motion Capture and Retargeting

- [Mixamo](https://www.mixamo.com/) - Free character animations and an accessible motion-capture library.
- [Rokoko](https://www.rokoko.com/) - Motion capture hardware, video capture, and Blender integration.
- [Rokoko Blender Add-on](https://support.rokoko.com/hc/en-us/articles/4410904696721-Blender) - Import and retarget Rokoko motion in Blender.
- [DeepMotion](https://www.deepmotion.com/) - AI video-to-motion capture and animation tools.
- [Plask](https://plask.ai/) - Browser-based AI motion capture and retargeting.
- [Move AI](https://www.move.ai/) - Markerless video motion capture with FBX and BVH export for Blender pipelines.
- [Cascadeur](https://cascadeur.com/) - Physics-assisted character animation, mocap cleanup, and retargeting companion to Blender.
- [CMU Graphics Lab Motion Capture Database](http://mocap.cs.cmu.edu/) - Classic free BVH and ASF/AMC dataset for practice and retargeting tests.
- [AMASS Archive](https://amass.is.tue.mpg.de/) - Unified motion-capture dataset in SMPL format, useful for research and ML-driven animation.
- [MoCap Online Blender Guide](https://mocaponline.com/blogs/mocap-news/blender-motion-capture-guide) - Practical FBX and BVH import, retargeting, cleanup, and export walkthrough.
- [Blender Retargeting Documentation](https://docs.blender.org/manual/en/latest/animation/armatures/posing/bone_constraints/index.html) - Core constraints used to adapt motion between rigs.

### Animation Practice

- [11 Second Club](https://www.11secondclub.com/) - Monthly dialogue animation challenge and critique community.
- [Animation Mentor](https://www.animationmentor.com/) - Structured character-animation training with mentor feedback.
- [iAnimate](https://ianimate.net/) - Online animation workshops focused on production skills.
- [The Animator's Survival Kit](https://www.theanimatorssurvivalkit.com/) - Richard Williams' classic animation reference.
- [Animator Island](https://www.animatorisland.com/) - Exercises and explanations for animation fundamentals.

## Tools and Add-ons

### Character-Focused Tools

- [RetopoFlow](https://blendermarket.com/products/retopoflow) - Interactive retopology tools for production meshes.
- [Auto-Rig Pro](https://blendermarket.com/products/auto-rig-pro) - Rig creation, animation retargeting, and game-engine export.
- [Wiggle Bones](https://extensions.blender.org/add-ons/wiggle-bones) - Spring-physics secondary motion for character bones.
- [Wiggle 2 RTX Edition](https://extensions.blender.org/add-ons/wiggle-2/) - Maintained Wiggle 2 fork for procedural bone physics on newer Blender versions.
- [KeenTools FaceBuilder](https://keentools.io/) - Build head meshes from photo reference for likeness and face-tracked characters.
- [Faceit](https://faceit.io/) - Facial setup, expressions, and performance capture support.
- [Studio Library](https://studio-library.com/) - Pose and animation library for Blender and Maya workflows.
- [Blender Source Tools](https://developer.valvesoftware.com/wiki/Blender_Source_Tools) - Useful for Source-engine character import and export.
- [Game Rig Tools](https://blendermarket.com/products/game-rig-tools) - Game-oriented rigging and export helpers.

### General-Purpose Tools

- [Blender Extensions](https://extensions.blender.org/) - Search and install community extensions.
- [Blender Add-on Templates](https://docs.blender.org/api/current/info_quickstart.html) - Start writing Python tools for repetitive character tasks.
- [Node Wrangler](https://docs.blender.org/manual/en/latest/addons/node/node_wrangler.html) - Faster shader-node editing; bundled with Blender.
- [Rigify](https://docs.blender.org/manual/en/latest/addons/rigging/rigify/index.html) - A strong starting point for reusable body rigs.
- [Animation Nodes](https://animation-nodes.com/) - Node-based procedural animation and motion systems.
- [Blender Benchmark](https://opendata.blender.org/) - Compare hardware before committing to heavy character scenes.

## Assets and References

### Characters and Animation

- [Blender Studio Characters](https://studio.blender.org/characters/) - Production characters from Blender Studio projects.
- [Blender Studio Films](https://studio.blender.org/films/) - Open movies with downloadable production files, rigs, and assets.
- [Blender Demo Files](https://www.blender.org/download/demo-files) - Official demo scenes, including character animation and sculpting examples.
- [Animation Fundamentals Rigs](https://studio.blender.org/training/animation-fundamentals/) - Training characters built for practicing the animation principles.
- [Rain Character Animation Test](https://studio.blender.org/characters/rain) - Example character performance with production rig, lighting, and rendering.
- [Blender Studio Asset Library](https://studio.blender.org/asset-library/) - Production assets, rigs, and scene examples where available.
- [Mixamo](https://www.mixamo.com/) - Characters, motions, and a quick way to test a retargeting pipeline.
- [Sketchfab](https://sketchfab.com/) - Downloadable 3D references and character assets; check each license.
- [BlenderKit](https://www.blenderkit.com/) - Searchable asset library with Blender integration.
- [OpenGameArt](https://opengameart.org/) - Open-licensed game art, sprites, models, and animation resources.
- [CMU Graphics Lab Motion Capture Database](http://mocap.cs.cmu.edu/) - Free BVH motion data for retargeting practice.
- [MoCap Online Free Pack](https://mocaponline.com/products/free-motion-capture-pack) - Free FBX motion pack for testing import and retargeting workflows.

### Materials, HDRIs, and Textures

- [Poly Haven](https://polyhaven.com/) - CC0 HDRIs, textures, and models for look development.
- [ambientCG](https://ambientcg.com/) - Free PBR materials, HDRIs, and texture maps.
- [CGBookcase](https://www.cgbookcase.com/) - Free PBR textures for clothing, props, and environments.
- [TextureCan](https://www.texturecan.com/) - Free PBR texture resources.
- [HDRI Haven](https://polyhaven.com/hdris) - HDRI lighting reference and free environment maps.

### Pose and Anatomy Reference

- [Posemaniacs](https://www.posemaniacs.com/) - 3D pose and anatomy reference.
- [Quickposes](https://quickposes.com/) - Timed gesture and figure-drawing practice.
- [SketchDaily Reference](https://reference.sketchdaily.net/) - Configurable figure and pose reference generator.
- [Bodies in Motion](https://www.bodiesinmotion.photo/) - High-quality movement reference photography.
- [Proko](https://www.proko.com/) - Anatomy, gesture, and figure-drawing lessons.

Always check the license for downloaded characters, animations, textures, and reference images before using them in a commercial project.

## Learning

### Blender and Character Courses

- [Blender Studio Training](https://studio.blender.org/training/) - Official production training, including character and animation work.
- [Blender Fundamentals](https://studio.blender.org/training/fundamentals/) - Structured introduction to Blender's core workflows.
- [CG Cookie](https://cgcookie.com/) - Blender courses, character projects, and community critique.
- [FlippedNormals](https://flippednormals.com/) - Character art, sculpting, texturing, and production courses.
- [School of Motion](https://www.schoolofmotion.com/) - Animation principles and motion-design education.
- [Blender Artists Tutorials](https://blenderartists.org/c/tutorials/30) - Community tutorials and workflow discussions.

### Channels and Short Tutorials

- [Blender Secrets](https://www.youtube.com/@BlenderSecrets) - Short, practical Blender workflow tips.
- [Grant Abbitt](https://www.youtube.com/@grabbitt) - Approachable modeling, sculpting, and animation lessons.
- [Dikko](https://www.youtube.com/@Dikko) - Character modeling, topology, and rigging tutorials.
- [Ryan King Art](https://www.youtube.com/@RyanKingArt) - Blender modeling, materials, and technical workflows.
- [Pierrick Picaut](https://www.youtube.com/@PierrickPicaut_Animation) - Character animation and rigging education.
- [Blender Studio YouTube](https://www.youtube.com/@BlenderStudio) - Open-movie production talks and behind-the-scenes videos.
- [YanSculpts](https://www.youtube.com/@yansculpts) - Blender sculpting courses, anatomy, and character creation.
- [Danny Mac 3D](https://www.youtube.com/@DannyMac3d) - Stylized character creation in Blender.
- [Royal Skies](https://www.youtube.com/@TheRoyalSkies) - Technical Blender workflows, including retopology and game pipelines.
- [BlenderNation](https://www.blendernation.com/) - News hub collecting Blender tutorials, add-ons, and character-art showcases.

## Production Resources

### Rendering and Look Development

- [Cycles](https://docs.blender.org/manual/en/latest/render/cycles/index.html) - Physically based renderer for final-quality character shots.
- [Eevee](https://docs.blender.org/manual/en/latest/render/eevee/index.html) - Fast real-time renderer for previews and stylized work.
- [Color Management](https://docs.blender.org/manual/en/latest/render/color_management.html) - Keep viewport, render, and compositing color consistent.
- [Compositor](https://docs.blender.org/manual/en/latest/compositing/index.html) - Add grading, glare, depth effects, and final image treatment.
- [Freestyle](https://docs.blender.org/manual/en/latest/render/freestyle/index.html) - Generate line art for stylized character renders.
- [Grease Pencil](https://docs.blender.org/manual/en/latest/grease_pencil/index.html) - Combine 2D line work with 3D character scenes.

### Pipeline and File Management

- [Library Overrides](https://docs.blender.org/manual/en/latest/files/linked_libraries/library_overrides.html) - Customize linked characters without breaking the source asset.
- [Linked Libraries](https://docs.blender.org/manual/en/latest/files/linked_libraries/index.html) - Share rigs, characters, and environments across shots.
- [Blender Asset Libraries](https://docs.blender.org/manual/en/latest/files/asset_libraries/index.html) - Configure reusable asset locations.
- [Alembic](https://docs.blender.org/manual/en/latest/files/import_export/alembic.html) - Exchange baked geometry and animation caches.
- [USD](https://docs.blender.org/manual/en/latest/files/import_export/usd.html) - Exchange scenes and assets with a wider production pipeline.
- [FBX](https://docs.blender.org/manual/en/latest/files/import_export/fbx.html) - Common interchange format for game engines and DCC applications.
- [glTF](https://docs.blender.org/manual/en/latest/addons/import_export/scene_gltf2.html) - Web and real-time delivery format for skinned characters and animation.

### Useful Python Ideas

- Batch rename meshes, materials, bones, and actions consistently.
- Validate that every deforming mesh has the expected armature and vertex groups.
- Create one-click scripts for facial expression libraries and pose saving.
- Export an animation-only file separately from the editable character source.
- Generate thumbnails and metadata for characters in the Asset Browser.

## Community

- [Blender Artists](https://blenderartists.org/) - Long-form Blender discussions, artwork, and troubleshooting.
- [Blender Chat](https://chat.blender.org/) - Real-time community chat hosted by the Blender community.
- [Blender Stack Exchange](https://blender.stackexchange.com/) - Searchable technical questions and answers.
- [Blender Artists Character Art](https://blenderartists.org/c/characters/6) - Character-focused artwork and feedback.
- [r/blender](https://www.reddit.com/r/blender/) - General Blender community and project sharing.
- [r/animation](https://www.reddit.com/r/animation/) - Animation discussion, critique, and reference.
- [Blender Conference](https://conference.blender.org/) - Talks and presentations from the Blender ecosystem.
- [Blender Development Fund](https://fund.blender.org/) - Support the development of Blender and its open tools.
- [BlenderNation](https://www.blendernation.com/) - News, tutorials, and character-art showcases from the Blender community.

## Character Workflow Checklist

- [ ] Gather front, side, three-quarter, expression, and costume references.
- [ ] Confirm the character's intended use: still render, film, game, VR, or real-time web.
- [ ] Block the silhouette and test the character in a neutral pose.
- [ ] Keep transforms applied and name objects, materials, collections, and actions clearly.
- [ ] Build topology that supports the intended deformation and facial expressions.
- [ ] Unwrap UVs and test texture density before painting detail.
- [ ] Test the eyes, mouth, hands, elbows, knees, and shoulders early.
- [ ] Create a small expression set before committing to a full facial rig.
- [ ] Animate a short pose test before finalizing weights.
- [ ] Check contact, arcs, timing, overlap, and silhouette at the final camera angle.
- [ ] Create a low-cost preview scene before starting final renders.
- [ ] Verify asset licenses and export settings before publishing.

## Contributing

Suggestions are welcome. Please submit resources that are directly useful for Blender character creation or animation.

When adding a link:

- Prefer official documentation, maintained projects, or established learning resources.
- Include a short description that explains why the resource is useful.
- Put the resource in the most specific existing section.
- Check that the link works and state a license when the resource distributes assets.
- Avoid duplicate links, referral links, and resources that only apply to unrelated Blender workflows.

Individual resources retain their own licenses; check each project before reuse.
