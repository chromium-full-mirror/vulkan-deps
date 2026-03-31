# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '32a3a77b0dc87832e8f0c38b581812562252f3b3',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '9be945a82df81fda32e1fe01a1bfffb1acf2745e',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '6dd7ba990830f7c15ac1345ff3b43ef6ffdad216',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'd7ba8c9fc218830544008cb71e4618adb1c56e12',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'f07ffc2cf2cd356927dee964fc0a35b5cfaeb789',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '385d337b64b09884a450c053b70beb1d7cc1ad57',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '90bf5bc4fd8bea0d300f6564af256a51a34124b8',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '5cbca997c1f916026670ffc8d6890ef9f1cd788d',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'e322daf444f214127a3341ae3ce5165a880548dc',
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
