# Hairstyle Taxonomy

Our hairstyle taxonomy consists of 18 attributes.
There are ten global attributes which are based on the whole hairstyle, for example the shape of the hairline or surface appearance of the hair.
The scalp is divided into eight regions and each region is annotated with eight local attributes, such as length and strand styling.
So in total each hairstyle has 74 taxonomic labels.
While we hope that the taxonomy presented is sufficiently fair, objective and complete, we recognize that it is likely impossible for it to be truly complete.
We therefore encourage future work to extend the taxonomy as required and contribute any modifications back to this repository.
Below is a graphical representation of the taxonomy.

## Global Attributes

Annotated once per hairstyle.

| Attribute | &nbsp;&nbsp;&nbsp;Values&nbsp;&nbsp;&nbsp; | | | | | | | |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Bangs Style | None ![none](graphics/ms_bangs_none.jpg) | Straight ![straight](graphics/ms_bangs_straight.jpg) | V-shape ![v](graphics/ms_bangs_vshaped.jpg) | U-shape ![u](graphics/ms_bangs_ushape.jpg) | Inverted U ![inverted u](graphics/ms_bangs_invertedushape.jpg) | Inverted V ![inverted v](graphics/ms_bangs_invertedvshape.jpg) | Diagonal R/L ![diag r/l](graphics/ms_bangs_diagonal_toprightobottomleft.jpg) | Diagonal L/R ![diag l/r](graphics/ms_bangs_diagonal_toplefttobottomright.jpg) |
| Bangs Length | Above ![above](graphics/ms_hairlength_bangs_aboveeyebrows_v02.jpg) | To ![to](graphics/ms_hairlength_bangs_eyebrows_v02.jpg) | Below ![below](graphics/ms_hairlength_bangs_beloweyebrows_v02.jpg) |
| Accessories | None ![none](graphics/ms_hairaccessories_none.jpg) | Headband ![headband](graphics/ms_hairaccessories_headband.jpg) | Ribbon ![ribbon](graphics/ms_hairaccessories_ribbonsandcords.jpg) | Hairnet ![hairnet](graphics/ms_hairaccessories_hairnet.jpg) | Scrunchy ![scrunchy](graphics/ms_hairaccessories_elastichairtie_scrunchie.jpg) | Comb ![comb](graphics/ms_hairaccessories_comb.jpg) | Clips ![clips](graphics/ms_hairaccessories_clips.jpg) | Beads ![beads](graphics/ms_hairaccessories_beads.jpg) |
| Parting | Center ![center](graphics/ms_partinglocation_central.jpg) | Right ![right](graphics/ms_partinglocation_rightside.jpg) | Left ![left](graphics/ms_partinglocation_leftside.jpg) | Diagonal ![diagonal](graphics/ms_partinglocation_diagonal.jpg) | Zig-Zag ![zigzag](graphics/ms_partinglocation_zigzag.jpg) | Other ![other](graphics/ms_partinglocation_other.jpg) |
| Hairline Shape | Straight ![straight](graphics/ms_hairline_straight.jpg) | Bell-Shaped ![bell](graphics/ms_hairline_bellshaped.jpg) | Receding ![receding](graphics/ms_hairline_receding_v02.jpg) | Widows-Peak ![widows peak](graphics/ms_hairline_widowspeak.jpg)| Uneven ![uneven](graphics/ms_hairline_uneven.jpg) | Unknown ![unknown](graphics/ms_hairline_idontknow.jpg) |
| Hairline Position | High ![high](graphics/ms_hairlineposition_high_v02.jpg) | Medium ![medium](graphics/ms_hairlineposition_medium.jpg) | Low ![low](graphics/ms_hairlineposition_low.jpg) | Unknown ![unknown](graphics/ms_hairlineposition_idontknow.jpg) |
| Hairline Visibility | Full ![full](graphics/ms_hairlinevisibility_fully.jpg) | Partial Left ![partial l](graphics/ms_hairlinevisibility_partiallyvisible_rightcovered.jpg) | Partial Right ![partial r](graphics/ms_hairlinevisibility_partiallyvisible_leftcovered.jpg) | None ![partial l](graphics/ms_hairlinevisibility_notvisible.jpg) |
| Surface | Matte ![matte](graphics/ms_surfaceappearance_matte.jpg) | Shiny ![shiny](graphics/ms_surfaceappearance_shiny.jpg) | Very Shiny ![v shiny](graphics/ms_surfaceappearance_veryshinyoiled.jpg) | Wet ![wet](graphics/ms_surfaceappearance_wetlook.jpg) |
| Baby Hair | None ![none](graphics/ms_babyhair_none.jpg) | Unstyled ![unstyled](graphics/ms_babyhair_unstyled.jpg) | Styled ![styled](graphics/ms_babyhair_styled.jpg) | Unkown ![unkown](graphics/ms_babyhair_idontknow_v02.jpg) |
| Attribute Varies | No![no](graphics/ms_hairattributechange_no.jpg) | Yes![yes](graphics/ms_hairattributechange_yes.jpg) |

## Scalp Regions

| Front | Top | Crown | Nape | Right Side | Right Temple | Left Temple | Left Side |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| ![front](graphics/ms_region_front.jpg) | ![top](graphics/ms_region_top.jpg) | ![crown](graphics/ms_region_crown.jpg) | ![nape](graphics/ms_region_nape.jpg) | ![right side](graphics/ms_region_sideright.jpg) | ![right temple](graphics/ms_region_templeright.jpg) | ![left side](graphics/ms_region_sideleft.jpg) | ![left temple](graphics/ms_region_templeleft.jpg) |

## Local Attributes

Annotated once per scalp region for each hairstyle.

| Attribute | &nbsp;&nbsp;&nbsp;&nbsp;Values&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Hair Type | Coily ![coily](graphics/ms_hairtype_coily.jpg) | Curly ![curly](graphics/ms_hairtype_curly.jpg) | Wavy ![wavy](graphics/ms_hairtype_wavy.jpg) | Straight ![straight](graphics/ms_hairtype_straight.jpg) |
| Strand Styling | None ![none](graphics/ms_strandstyling_none.jpg) | Twists ![twists](graphics/ms_strandstyling_ringletstwists.jpg) | Dreadlocks ![dreadlocks](graphics/ms_strandstyling_dreadlocks.jpg) | Braids ![braids](graphics/ms_strandstyling_braids.jpg) | Other ![other](graphics/ms_strandstyling_other.jpg) |
| Strand Thickness | Large ![large](graphics/ms_strandstyling_thickness_large.jpg) | Medium ![medium](graphics/ms_strandstyling_thickness_medium.jpg) | Micro ![micro](graphics/ms_strandstyling_thickness_micro.jpg) |
| Gathered | None ![none](graphics/ms_hairgathered_none.jpg) | Behind-Ear ![behind ear](graphics/ms_hairgathered_hairtuckedbehindear.jpg) | Bun ![bun](graphics/ms_hairgathered_bun_single.jpg) | Buns ![buns](graphics/ms_hairgathered_bun_multiple.jpg) | Ponytail ![ponytail](graphics/ms_hairgathered_ponytail_single.jpg) | Ponytails ![ponytails](graphics/ms_hairgathered_ponytail_multiple.jpg) | On Skin ![on skin](graphics/ms_hairgathered_attachedtoskin.jpg) | Knot ![knot](graphics/ms_hairgathered_knot_single_v02.jpg) | Knots ![knots](graphics/ms_hairgathered_knot_multiple.jpg) | Other ![other](graphics/ms_hairgathered_other.jpg) | Unknown ![unknown](graphics/ms_hairgathered_gatheringnotvisible_v02.jpg) |
| Direction | Down ![down](graphics/ms_hairdirection_brusheddown.jpg) | Side ![side](graphics/ms_hairdirection_brushed_swepttoside.jpg) | Up ![up](graphics/ms_hairdirection_brushed_gatheredup.jpg) | Out ![out](graphics/ms_hairdirection_pointingout.jpg) |
| Length | Bald ![bald](graphics/ms_hairlength_bald.jpg) | Shaved ![shaved](graphics/ms_hairlength_shavedroots.jpg) | Very Short ![very short](graphics/ms_hairlength_veryshort.jpg) | Short ![short](graphics/ms_hairlength_short.jpg) | Ear ![ear](graphics/ms_hairlength_earlength.jpg) | Chin ![chin](graphics/ms_hairlength_chinlength.jpg) | Shoulder ![shoulder](graphics/ms_hairlength_shoulderlength.jpg) | Armpit ![armpit](graphics/ms_hairlength_armpitlength_v02.jpg) | Mid-Back ![mid back](graphics/ms_hairlength_midbacklength_v02.jpg) | Waist ![armpit](graphics/ms_hairlength_waistlength_v02.jpg) |
| Layering | None ![none](graphics/ms_layering_singlelength.jpg) | Textured ![textured](graphics/ms_layering_textured_v02.jpg) | Taper ![taper](graphics/ms_layering_taper.jpg) |  Fade ![fade](graphics/ms_layering_fade.jpg) |
| Decoration | None ![none](graphics/ms_decorativepatterns_no.jpg) | Decorated ![dec](graphics/ms_decorativepatterns_yes.jpg) |