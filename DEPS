# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '8590f62c145549b30e07d6714afe6158174574f7',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '7f104e857c1c93558b3bb15e35aabc4b02a8198a',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'f013f08e4455bcc1f0eed8e3dd5e2009682656d9',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '246daf246bb17336afcf4482680bba434b1e5557',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '595c8d4794410a4e64b98dc58d27c0310d7ea2fd',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'e72ca6b705fe2fed43325b189e6122a5ce81a4af',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '46df205dcad665b652f57ee580d78051925b296a',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '45b881573538f8e481cb6e1d811a9076be6920c1',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '64cca2a382781cc66f2f28121a170bd1dac5486e',
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
