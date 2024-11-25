# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'd19905df53ce4b995d270c9c5f0cc53ee779729e',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '4e9bb6f426cf776910848441da65cc14f1146e77',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '36d5e2ddaa54c70d2f29081510c66f4fc98e5e53',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'f3c4a5053f1bd34056282e56659659873f9d47ad',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '36872f9062b17b1a30b8ed1d81ca5ea6bb608a72',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '081b529a37f43249225114c4c0dea12a29ce605f',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '2ed61c1d34f95fdeeff09befd798e18845c9f95b',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'b538fb5b08513aa78346cd414ad5e576a2a3e920',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'c82950cc132ff9d94795cc3b7eb9aa55d3f15f94',
}

deps = {
  'glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
  },

  'lunarg-vulkantools/src': {
    'url': '{chromium_git}/external/github.com/LunarG/VulkanTools@{lunarg_vulkantools_revision}',
  },

  'spirv-cross/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Cross@{spirv_cross_revision}',
  },

  'spirv-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Headers@{spirv_headers_revision}',
  },

  'spirv-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Tools@{spirv_tools_revision}',
  },

  'vulkan-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Headers@{vulkan_headers_revision}',
  },

  'vulkan-loader/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Loader@{vulkan_loader_revision}',
  },

  'vulkan-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Tools@{vulkan_tools_revision}',
  },

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
